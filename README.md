# **OVH Hardware Checker**

A front-end only, in-browser terminal for checking OVH server hardware specifications. All API keys and history are stored locally in your browser's localStorage.

### **Live Demo**

[**You can try it live here\!**](https://zakkuuno.github.io/ovh-hardware-checker/)

### **Features**

* **Secure & Private:** All API keys are stored *only* in your browser's local storage. They are never sent to any server except the OVH API.  
* **Server History:** Automatically saves a cache of checked servers in the sidebar.  
* **Command History:** Use the up/down arrows to cycle through previous commands.

### **How to Use**

1. **Get API Credentials:**  
   * Open the **Settings** (⚙️ icon).  
   * You will need to generate API keys from OVH. You can use this link: [https://api.ovh.com/createToken/](https://api.ovh.com/createToken/)  
   * When creating your token, you need to grant GET access to the /dedicated/server/\* endpoints.  
2. **Enter Keys:** Copy the Application Key, Application Secret, and Consumer Key into the settings modal and save.  
3. **Start Checking:** You can now use the check command\!

### **⚠️ Security Warning**

This tool stores your API keys, including your **Application Secret** and **Consumer Key**, in your browser's local storage. While this is convenient, be aware of the risks:

* **DO NOT** use this on a public or shared computer.  
* **DO NOT** enter your keys if you are on an untrusted network.  
* I am **NOT** responsible for any misuse or loss of credentials.

### **License**

This project is licensed under the **MIT License**.

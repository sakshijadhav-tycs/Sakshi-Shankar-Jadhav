 **Keylogger Detector – Project Summary**

This project is a **desktop application** built using **Python** and **Tkinter GUI**. It helps users **detect and remove keyloggers** (malicious programs that secretly record what you type).

 **What the App Does:**

1.  **Welcome Page**
    
    *   Shows a nice interface with buttons to:
        
        *   Start a keylogger scan
            
        *   View running system processes
            
        *   See system health info
            
        *   Exit the app
            
2.  **Keylogger Detection**
    
    *   When the user clicks **Start Scan**, the app:
        
        *   Shows a progress bar while scanning
            
        *   Looks for known keylogger-related process names (like "logger", "hook", "spy", etc.)
            
        *   Uses the psutil library to check running processes
            
3.  **Detection Result**
    
    *   If keylogger processes are found:
        
        *   Shows them in a new window with details (name, PID)
            
        *   Offers a **"Terminate Keyloggers"** button to stop those processes
            
4.  **Other Features**
    
    *   **View Running Processes**: Displays all active processes on the system
        
    *   **System Health Info**: Shows CPU usage, memory usage, total processes, and system boot time
        
    *   **Exit Button**: Allows safe app exit with confirmation
        

 Technologies Used:

*   **Python**
    
*   **Tkinter** – for GUI
    
*   **psutil** – to monitor processes and system info
    

 Overall Purpose:

This app provides **a simple way to check for and remove suspicious keylogger software**, helping users **protect their privacy and security**.

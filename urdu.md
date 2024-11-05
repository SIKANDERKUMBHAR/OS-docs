
---

### **File Management System OS mein**

**File Management System** (FMS) OS ka wo hissa hai jo disk par data ko store, organize, retrieve, aur manage karta hai. Yahan kuch uske zaroori functions diye gaye hain:

#### 1. **File Operations**
   - FMS user ko basic file operations jaise ke file create karna, parhna (read), likhna (write), rename karna, aur delete karne ki sahulat deta hai.
   - Yeh operations users ko data aur files ke sath interact karne ka tareeqa faraham karti hain.

#### 2. **File Organization**
   - **Hierarchical Directory Structure**: Files ko directories (ya folders) aur subdirectories mein organize kiya jata hai. Is structure ki madad se users ko files ko dhoondhna aur manage karna aasaan hota hai.
   - **File Extensions**: Files ko aksar unke extensions (maslan, `.txt`, `.jpg`) ke zariye pehchana jata hai, jo OS ko file type samajhne aur correct application se open karne mein madad dete hain.

#### 3. **File Access Control**
   - OS permissions faraham karta hai (jaise ke read, write, execute) jo yeh decide karti hain ke kaun file ko access ya modify kar sakta hai. Is se security ensure hoti hai aur unauthorized access roka jata hai.
   - **File Ownership**: OS har file ke liye ek malik (owner) assign karta hai jo yeh decide karta hai ke kis user ya process ko file par control hoga.

#### 4. **File Storage aur Retrieval**
   - **Logical File System**: OS ek logical view banata hai files aur folders ka, jo physical storage ke details ko abstract karta hai.
   - **File Allocation**: System decide karta hai ke files disk par kahan aur kaise store hongi (maslan, contiguous, linked, ya indexed allocation methods).

#### 5. **File Protection aur Integrity**
   - System ensure karta hai ke files corruption ya accidental loss se mehfooz rahein. Iske liye backup systems, journaling, ya RAID jaise mechanisms istemal kiye jaate hain.

#### 6. **File Sharing**
   - OS file sharing ko support karta hai, ya toh files ko copy karke ya ek hi file ko multiple users ya processes ke liye access dene ke zariye.

---

### **Device Management System OS mein**

**Device Management System** hardware devices (jaise ke printers, hard drives, keyboards) aur OS ke darmiyan communication ko handle karta hai.

#### 1. **Device Drivers**
   - OS **device drivers** ka istemal karta hai, jo ek specific program hota hai aur device hardware aur OS ke darmiyan translation ka kaam karta hai. Har hardware device ka apna driver hota hai jo ensure karta hai ke device sahi tareeqa se OS ke sath communicate kare.

#### 2. **Device Controllers**
   - Devices ko hardware controllers ke zariye manage kiya jata hai, jo physical devices ke operations ko dekhte hain. OS controllers ke sath communicate karta hai taake data bheja aur receive kiya ja sake.

#### 3. **I/O Operations**
   - OS input/output (I/O) operations ko handle karne ka tareeqa faraham karta hai. Chahe wo keyboard se data parhna ho ya disk par likhna ho, device management system yeh I/O requests ko efficiently schedule karta hai.
   - **Buffering**: Data ko temporary tor par memory (buffers) mein rakha jata hai jab tak wo device aur OS ke darmiyan transfer ho raha ho, takay smooth operation ensure kiya ja sake.

#### 4. **Device Allocation**
   - OS ensure karta hai ke devices ko different processes ya users ke darmiyan fair tor par allocate kiya jaye. Maslan, agar multiple processes ko printer chahiye ho, toh OS access ko is tarah manage karta hai ke tasks conflict na karein.

#### 5. **Interrupt Handling**
   - Devices aksar interrupts (signals) ke zariye CPU se tawajjo talab karte hain. OS in interrupts ko handle karta hai aur ensure karta hai ke device ko zaroori tawajjo milay bina system performance ko disturb kiye.

#### 6. **Device Monitoring aur Maintenance**
   - OS devices ka status monitor karta hai (maslan, disk ki health, printer availability) aur maintenance tools faraham karta hai, jaise ke disk defragmentation ya device drivers ka update.

---

### **Summary**
- **File Management System**: File operations, organization, access control, aur storage management ke zimmedar hota hai.
- **Device Management System**: Hardware devices ko drivers ke zariye manage karta hai, I/O operations ko handle karta hai, device allocation aur interrupts ko control karta hai.

---


**File Management System OS mein**

**File Management System (FMS)** OS ka wo hissa hai jo disk par data ko store, organize, retrieve, aur manage karta hai. Yahan kuch uske zaroori functions diye gaye hain:

1. **File Operations**  
   FMS user ko basic file operations jaise ke file create karna, parhna (read), likhna (write), rename karna, aur delete karne ki sahulat deta hai.  
   Yeh operations users ko data aur files ke sath interact karne ka tareeqa faraham karti hain.

2. **File Organization**  
   - **Hierarchical Directory Structure**: Files ko directories (ya folders) aur subdirectories mein organize kiya jata hai. Is structure ki madad se users ko files ko dhoondhna aur manage karna aasaan hota hai.  
   - **File Extensions**: Files ko aksar unke extensions (maslan, .txt, .jpg) ke zariye pehchana jata hai, jo OS ko file type samajhne aur correct application se open karne mein madad dete hain.

3. **File Access Control**  
   OS permissions faraham karta hai (jaise ke read, write, execute) jo yeh decide karti hain ke kaun file ko access ya modify kar sakta hai. Is se security ensure hoti hai aur unauthorized access roka jata hai.  
   - **File Ownership**: OS har file ke liye ek malik (owner) assign karta hai jo yeh decide karta hai ke kis user ya process ko file par control hoga.

4. **File Storage aur Retrieval**  
   - **Logical File System**: OS ek logical view banata hai files aur folders ka, jo physical storage ke details ko abstract karta hai.  
   - **File Allocation**: System decide karta hai ke files disk par kahan aur kaise store hongi (maslan, contiguous, linked, ya indexed allocation methods).

5. **File Protection aur Integrity**  
   System ensure karta hai ke files corruption ya accidental loss se mehfooz rahein. Iske liye backup systems, journaling, ya RAID jaise mechanisms istemal kiye jaate hain.

6. **File Sharing**  
   OS file sharing ko support karta hai, ya toh files ko copy karke ya ek hi file ko multiple users ya processes ke liye access dene ke zariye.

---

**Device Management System OS mein**

**Device Management System** hardware devices (jaise ke printers, hard drives, keyboards) aur OS ke darmiyan communication ko handle karta hai.

1. **Device Drivers**  
   OS device drivers ka istemal karta hai, jo ek specific program hota hai aur device hardware aur OS ke darmiyan translation ka kaam karta hai. Har hardware device ka apna driver hota hai jo ensure karta hai ke device sahi tareeqa se OS ke sath communicate kare.

2. **Device Controllers**  
   Devices ko hardware controllers ke zariye manage kiya jata hai, jo physical devices ke operations ko dekhte hain. OS controllers ke sath communicate karta hai taake data bheja aur receive kiya ja sake.

3. **I/O Operations**  
   OS input/output (I/O) operations ko handle karne ka tareeqa faraham karta hai. Chahe wo keyboard se data parhna ho ya disk par likhna ho, device management system yeh I/O requests ko efficiently schedule karta hai.  
   - **Buffering**: Data ko temporary tor par memory (buffers) mein rakha jata hai jab tak wo device aur OS ke darmiyan transfer ho raha ho, takay smooth operation ensure kiya ja sake.

4. **Device Allocation**  
   OS ensure karta hai ke devices ko different processes ya users ke darmiyan fair tor par allocate kiya jaye. Maslan, agar multiple processes ko printer chahiye ho, toh OS access ko is tarah manage karta hai ke tasks conflict na karein.

5. **Interrupt Handling**  
   Devices aksar interrupts (signals) ke zariye CPU se tawajjo talab karte hain. OS in interrupts ko handle karta hai aur ensure karta hai ke device ko zaroori tawajjo milay bina system performance ko disturb kiye.

6. **Device Monitoring aur Maintenance**  
   OS devices ka status monitor karta hai (maslan, disk ki health, printer availability) aur maintenance tools faraham karta hai, jaise ke disk defragmentation ya device drivers ka update.

---

**Summary**  
- **File Management System**: File operations, organization, access control, aur storage management ke zimmedar hota hai.  
- **Device Management System**: Hardware devices ko drivers ke zariye manage karta hai, I/O operations ko handle karta hai, device allocation aur interrupts ko control karta hai.

---



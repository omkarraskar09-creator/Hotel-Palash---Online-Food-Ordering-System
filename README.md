# Hotel-Palash---Online-Food-Ordering-System
An elegant, end-to-end web application designed to bridge the gap between heritage "Chulha" (wood-fired) culinary traditions and modern digital convenience. Tailored specifically for Hotel Palash (located on the Tasgaon-Karad Road in Kundal) , this platform enables customers to seamlessly register, log in, browse the digital menu, manage a virtual cart, and generate instant bills. It also features an integrated administrative overview mechanism for management tracking.  

🚀 Features :

Customer Interface-

Secure Authentication: Comprehensive User Registration (register.html) and Secure Login (login.html) utilizing localStorage persistence.  
Intuitive Ordering Dashboard: Clean dropdown selection for iconic menu items (Veg Thali, Paneer Butter Masala, Fried Rice, etc.) along with explicit quantity management.  
Dynamic Cart & Bill Calculation: Instant billing calculations including a breakdown of subtotal, automated 5% GST addition, and exact grand totals.Instant Receipt Printing: Native window print execution directly from the receipt dashboard.  
Owner & Administrative Controls Order Control Panel: Dedicated view within the system providing owners real-time monitoring of all incoming customer orders logged during the business cycle.  
Data Integrity: Simple client-side data persistence ensuring operational continuity across sessions without external heavy infrastructure setup.

🛠️ Tech Stack Frontend: HTML5, CSS3 (Linear gradients, custom keyframe transitions, and responsive box shadows)

Scripting Language: Vanilla JavaScript (ES6+)

State Management / Persistence: Browser-based Web Storage API (localStorage)

📂 Project Structure

Bash

├── index.html        # Welcome/Landing page with dynamic CSS animations

├── register.html     # Client registration handling validation logic 

├── login.html        # Authentication validator parsing stored credentials

└── wd.html           # Main dashboard engine handling order placement, calculations, & receipt generation

⚙️ How to Run LocallyClone the Repository:Bashgit clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git
Launch the App:Simply navigate to the project directory and double-click index.html to open it in any modern web browser (Chrome, Edge, Safari, Firefox). No heavy server execution or database installation required!

🔮 Future Enhancements Planned milestones to scale the application into a commercial-grade product line: 

Payment Gateway Integration: Adding robust modules for UPI (Google Pay, PhonePe), credit/debit cards, and digital wallets. 

Automated Notifications: Transitioning system states via SMS/Email triggers when order status updates from "Pending" to "Out for Delivery". 

Native Mobile Application: Porting the existing interactive UI layout onto Android and iOS mobile platforms via wrapper ecosystems. 

Inventory Automation: Interlocking the kitchen stock levels directly with the menu selection arrays to dynamically disable items when raw inventory is exhausted.  

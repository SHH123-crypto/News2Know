#Title
News2Know
#How to Use: 
 How to Use
This script sends political or general news summaries to your phone via SMS using Python, the GNews API, and Gmail's SMTP server. Follow the steps below to run it:

🔧 Requirements
Python 3 installed

Internet connection

A Gmail account with App Passwords enabled

A U.S. phone number on AT&T, T-Mobile, Verizon, or Sprint

📦 Libraries Used
This script uses the following libraries:

json

requests

smtplib

sys

Make sure to install any missing libraries using pip:

bash
Copy
Edit
pip install requests
🚀 Running the Script
Run the Python script in your terminal or IDE.

Enter a news category when prompted. Choose from:

Copy
Edit
general, world, nation, business, technology, entertainment, sports, science and health
If you select "nation", the script filters articles based on political party keywords to highlight politically significant stories.

Enter your phone number (numbers only, no spaces or symbols).

Choose your mobile carrier from the following options:

Copy
Edit
att, tmobile, verizon, sprint
The script fetches top news headlines using the GNews API, composes a message, and sends it to your phone via SMS using Gmail's SMTP service.

If successful, you'll see:

mathematica
Copy
Edit
Message sent!

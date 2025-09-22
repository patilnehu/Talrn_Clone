Talrn Clone – React Task Assessment

This project is a React.js assessment task replicating the core flows of Talrn.com
, including the homepage and the /join registration flow with OTP-based email verification.

🚀 Live Demo

🔗 https://talrn-clone.vercel.app

🛠️ Tech Stack

React.js (with Vite)

TypeScript

React Router DOM – for routing

TailwindCSS – for styling

EmailJS – for sending OTP emails

Vercel – for deployment

⚙️ Setup & Installation

Clone the repository

git clone https://github.com/patilnehu/Talrn_Clone.git
cd Talrn_Clone

Install dependencies

npm install

Run in development mode

npm run dev

Build for production

npm run build
npm run preview

🔑 EmailJS Configuration

This project uses EmailJS for sending OTPs.

To make it work:

Create an EmailJS
account.

Replace the following values in OrganizationForm.tsx (and IndividualForm.tsx if used):

service_qc42bjl → Your EmailJS Service ID

template_b1dopuf → Your Template ID

fTP2kZ98PDNwaqYW4 → Your Public Key

📂 Project Structure
src/
│── components/ # Shared UI components (Header, Footer, Forms, etc.)
│── pages/ # Page components (Home, Join, Verify, Success)
│── App.tsx # App entry with React Router setup
│── main.tsx # React DOM render
public/ # Static assets
vercel.json # SPA routing configuration for Vercel

✅ Features Implemented

Home page UI replicated from Talrn.com.

/join page with radio toggle for Organization and Individual forms.

Email OTP verification with 6-digit code.

LocalStorage used to persist OTP + email between pages.

Responsive design across devices.

Success page confirmation after verification.

📌 Deployment Notes

Hosted on Vercel with SPA fallback (vercel.json) to support React Router.

All client-side routes (/join, /verify, /success) work directly in browser.

📞 Contact

Developer: Neha Patil

Email: dev.nehapatil@gmail.com

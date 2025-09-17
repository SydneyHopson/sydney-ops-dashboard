# Sydney Ops Command Center

The **Sydney Ops Command Center** is a custom-built dashboard app designed to automate and visualize daily datacenter operations across FTY01–FTY02 and CCO06–07. It integrates shipment tracking, GDCO task monitoring, access coordination, and break/fix workflows into a single interactive interface.

## 🚀 Features

- 📦 **Shipment Tracker**  
  Visualizes received vs pending orders by PO, vendor, and datacenter.

- 🛠️ **GDCO Task Monitor**  
  Tracks task status by severity, location, and fulfillment ID. Includes escalation links and SOP references.

- 🧾 **Access Coordination Panel**  
  Monitors access requests, safety orientation status, and badge issuance.

- 🔄 **Break/Fix & RMA Tracker**  
  Displays urgent replacements, WAL creation, and GDCO intake status.

- 🌗 **Dark/Light Mode Toggle**  
  Switch between visual themes for comfort and accessibility.

- 📱 **Mobile View Optimization**  
  Responsive layout for phones and tablets.

- 🎙️ **Voice-Triggered Refresh**  
  Say “refresh dashboard” to pull the latest updates.

- 🔘 **Manual Refresh Button**  
  Instantly reload data with a single click.

## 🧠 Tech Stack

- **Frontend**: Next.js + TailwindCSS
- **Hosting**: Azure Static Web Apps / Vercel
- **Data Sources**:
  - Power BI (DC_InboundDeliveryManager_PO)
  - GDCO App / DCC CMMS
  - Microsoft Graph API (emails, calendar, Teams)

## 📦 Deployment

This app is designed to be deployed on:

- https://portal.azure.com
- https://vercel.com

## 📂 Folder Structure 



















## 🛠️ Setup Instructions

1. Clone the repo or upload the ZIP contents.
2. Run `npm install` to install dependencies.
3. Run `npm run dev` to start the development server.
4. Deploy to Azure or Vercel for production.

## 👤 Author

Built by **Sydney Hopson**  
Role: Datacenter Inv and Asset Tech  
Location: Atlanta  
Focus: FTY01–FTY02, CCO06–07

---

Let me know if you’d like to add badges, contributor credits, or a license section. I can also upload this directly if you give me access to your repo.

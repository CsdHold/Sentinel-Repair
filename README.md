# **Sentinel-Repair: ADA Mobility Services**

Sentinel-Repair is a responsive, single-page web application designed to help traveling individuals with disabilities quickly find certified repair shops, check real-time parts inventory, and arrange loaner equipment (such as wheelchairs, scooters, and hearing aids).

The platform features **ARIA** (Adaptive Repair Intelligence Assistant), an integrated 24/7 AI agent powered by the Google Gemini API, which acts as a concierge to guide users through emergency repairs and inventory checks.

## **Features**

* **Repair Shops Directory:** Browse, search, and filter ADA-certified repair shops by 24/7 availability and loaner equipment stock.  
* **Live Parts & Inventory:** Check real-time stock levels for specific mobility device parts (joysticks, batteries, casters, etc.) across partner shops.  
* **Interactive Map View:** A visual layout of the service area showing shop locations, status (Open/Closed), and user proximity.  
* **ARIA (AI Assistant):** A built-in chat panel that uses the Gemini API to answer natural language queries based on the platform's database of shops and inventory.  
* **AI-Powered Insights:**  
  * **Review Summaries:** Generate quick, AI-driven summaries of a shop's customer reviews and wait times.  
  * **Part Troubleshooting Guides:** Generate instant diagnostic and safety tips for specific equipment parts.  
* **Instant Booking:** A streamlined modal system to book appointments and request loaners to be dispatched to a terminal or hotel.  
* **Fully Responsive:** Built with a modern, mobile-first design using custom CSS variables, flexbox, and CSS grid.

## **Technologies Used**

* **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6+)  
* **Architecture:** Single-file component (No build steps or bundlers required)  
* **AI Integration:** Google Gemini API (gemini-3-flash-preview)  
* **Typography:** Inter & Space Grotesk (Google Fonts)

## **Getting Started**

Because Sentinel-Repair is built as a self-contained single file, setup is incredibly straightforward.

### **Prerequisites**

4. **Run the app:**  
   Simply double-click the HTML file to open it in your web browser, or use a tool like VS Code Live Server.

## **Database Structure**

Currently, the application uses mock JSON data embedded directly in the JavaScript for demonstration purposes:

* REPAIR\_SHOPS: Contains shop details, hours, wait times, ratings, and loaner availability.  
* PARTS\_INVENTORY: Contains part names, SKUs, stock quantities, pricing, and compatibility lists.

*Note: In a production environment, these arrays would be replaced with dynamic API calls to a backend database.*

## **Contributing**

Contributions, issues, and feature requests are welcome\! Feel free to check the [issues page](https://github.com/yourusername/sentinel-repair/issues).

1. Fork the Project  
2. Create your Feature Branch (git checkout \-b feature/AmazingFeature)  
3. Commit your Changes (git commit \-m 'Add some AmazingFeature')  
4. Push to the Branch (git push origin feature/AmazingFeature)  
5. Open a Pull Request

## **License**

Distributed under the MIT License. See LICENSE for more information.
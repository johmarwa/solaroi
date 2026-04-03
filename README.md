The `index.html` file serves as a frontend for a "Solar Calculator" application named Megatricity. It allows users to input solar-related parameters to calculate system specifications, economic metrics, and environmental impact, providing insights for potential solar installations.

### Key Features:
1. **Page Layout:**
   - Styled with a clean, responsive CSS for modern aesthetics.
   - Contains a header, input panels, result display sections, and a footer.

2. **Input Fields:**
   - Users can enter their monthly electricity bill, billing units (KES/kWh), type of building (domestic/commercial), and preference for a battery backup system.
   - Night backup percentage slider and dynamic dropdowns adjust options interactively.

3. **Dynamic Calculations:**
   - Automatic calculations for solar specifications, including solar panel capacity, inverter size, battery size, initial cost, return on investment (ROI), payback time, and net present value (NPV).
   - Currencies (KES, USD, EUR) and live exchange rates are incorporated for cost adaptations.

4. **Visualization:**
   - A chart illustrating "Lifetime Cash Flow Analysis".
   - Environmental impact metrics (e.g., CO₂ avoided, equivalent trees grown, coal consumption offset).

5. **Request a Quote Modal:**
   - Allows users to fill out a form with contact details to send a quote request to the Megatricity team.

6. **Technical Details:**
   - Includes a JavaScript-based financial model for solar energy ROI calculations.
   - Uses formulas to factor in parameters such as tariff escalation, solar degradation, and discount rates.

7. **Footer Notes:**
   - Provides disclaimers and links to official websites.

### Additional Code Highlights:
- **Interactivity:** Through JavaScript functions (e.g., `calc()`, `setCur()`, `syncSlider()`) for dynamic user experience and calculation updates.
- **Chart Rendering:** Handles profit/loss visualization dynamically using inline SVG.
- **Email Integration:** Prepares a mail request for quote submissions.

The page is feature-rich, combining ease of use with precise modeling for solar installation evaluation. It is designed to guide homeowners and businesses in their solar investment decisions.

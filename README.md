🧪 **Medical Biochemistry Assistant**

Medical Biochemistry Assistant is a comprehensive, single-page web application designed for laboratory specialists, residents, and healthcare professionals. It streamlines complex biochemical calculations, provides quick access to laboratory guidelines, and offers a personal note-taking interface.


🧮 **Advanced Clinical Calculators**

The "Calc" tab is the core of the app, housing 49 (just for now) clinical biochemistry calculators organized into a searchable grid. Each card opens a dedicated calculation view with labeled inputs, real-time results, and clinical interpretation. Every numeric input field carries a clickable unit badge that instantly converts between conventional and SI units — no manual math required. Results include color-coded interpretations (normal / borderline / abnormal) and collapsible reference lists citing the original literature. Calculators span nephrology (GFR, FENa, TTKG, KFRE), hematology (RBC indices, Mentzer, INR), acid-base & electrolytes (Anion Gap, Osmolality, Winters Formula, ABG Validation), hepatology (FIB-4, APRI, De Ritis, Light's Criteria), endocrinology (HOMA-IR, QUICKI, FAI, HbA1c), lipids (LDL by three methods, AIP, TyG), and laboratory technique (serial dilution planners, RCF↔RPM, D-Dimer converter). A live search bar with autocomplete lets you jump to any calculator by name or keyword. Deep linking is supported — every calculator has its own URL hash (e.g. #calc-gfr) so results can be bookmarked or shared directly. In the calc menu, you can change the test units you want to use by clicking on the unit. For more information, you can click the Info&Guide button within the tool.
<img width="2492" height="1443" alt="image" src="https://github.com/user-attachments/assets/13e9c4ca-91f1-4aab-8513-47d0ccbc7382" />


✅ **Quality Control and Practical Laboratory Tools**

The QC tab offers a complete set of laboratory quality control and analytical performance tools. The Levey-Jennings Simulator plots control charts from manually entered or Excel-uploaded QC data and automatically detects rule violations using configurable Westgard rules. The PBRTQC (EWMA & MA) module uses patient result distributions to monitor analytical stability in real time via Exponentially Weighted Moving Average or Moving Average methods. The Sigma Metric & Method Decision tool calculates the Sigma value from TEa, bias, and CV% to classify method performance and guide QC strategy selection using OPSpecs charts. The Delta Calculation (RCV) tool determines whether a change between two consecutive patient results is analytically or clinically significant using biological variation data. The Bland-Altman Plot enables method comparison by visualizing agreement and bias between two measurement techniques. The Carryover Analysis tool quantifies sample-to-sample carryover contamination on automated analyzers. The Measurement Uncertainty module calculates combined and expanded uncertainty according to GUM/ISO 15189 principles. The Individuality Index (II) evaluates whether population-based reference intervals are appropriate for a given analyte. The Glucometer QC Check tool assesses point-of-care glucose meter performance against ISO 15197 accuracy criteria. Finally, the Z-Score / SDI Calculator computes standardized deviation indices for external quality assessment (EQA/PT) scheme evaluation. For more information, you can click the Info&Guide button within the tool.
<img width="2517" height="1450" alt="image" src="https://github.com/user-attachments/assets/52a0ebbe-5fa9-4d87-9c0c-393665dd8955" />


📖 **Guide**

The Guide tab serves as a centralized resource hub for clinical laboratory professionals, bringing together the most frequently needed references, tools, and literature in one place. The Favorites section provides quick-access links to widely used biochemistry resources, including Mayo Clinic Labs (test catalog), Clinical Lab Diagnostics (online textbook), ADLM/AACC (lab medicine authority), Lab Tests Online (patient-friendly test explanations), the Harmonization Database (international measurands), QC Constellation (quality control app), CALIPER (pediatric reference intervals), Lab Error Finder, and the global lab community Reddit MedLab — as well as Turkish professional organizations such as TBD, TKBD, and KBUD. The Lab Digest section allows you to follow the latest publications from leading laboratory medicine journals in a unified feed: simply select the journals you wish to track and the number of recent articles to display, then click the Lab Digest button to browse the most current literature across all selected journals at once. Finally, the Laboratory Handbook section — designed primarily for Turkish users — provides direct access via Google Drive to official Turkish Ministry of Health documents, Medical Biochemistry regulations, circulars, and legislation, making it an essential reference for staying up to date with local regulatory requirements.
<img width="2492" height="1460" alt="image" src="https://github.com/user-attachments/assets/e2976f4d-e0e3-42d6-9f12-9e905c3e0dbb" />


✍🏻 **Take Notes**

The Notes tab provides a private, distraction-free text area where you can jot down personal observations, reminders, interpretation notes, or any laboratory-related information you wish to keep at hand. All content written here is stored locally on your device and browser — nothing is sent to any server, making it entirely private and accessible only to you. It is ideal for quickly saving reference values, case notes, or calculation results during your daily workflow without leaving the application.
<img width="2518" height="1455" alt="image" src="https://github.com/user-attachments/assets/8586de55-c917-4541-bc66-ca34ee6c0921" />


🧰 **Technologies Used**

HTML5: Semantic structure.

CSS3: Modern styling with CSS Variables (for theming), Flexbox, and Grid layouts.

JavaScript (ES6+): Core logic for calculations, DOM manipulation, state management, and LocalStorage.

FontAwesome: For UI icons.

Google Fonts: Typography (Inter font).


⚠️ **Disclaimer**

This software is developed as a Medical Biochemistry Assistant Tool for educational and general informational purposes only. The calculation results are intended to assist professionals but should not be used as the sole basis for medical diagnosis or treatment decisions. Results should always be evaluated in conjunction with clinical findings and laboratory reference ranges.

🤝 **Contact**

For feedback, suggestions, or error reporting:
Developer: Belgin ŞARA, MD
Github: https://github.com/belqin
Email: belginsaraa@gmail.com

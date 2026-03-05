# cream-calc
facial cream elements and formula caculator
Professional Face Cream Formulation Lab (AI-Enhanced)
A high-precision web application designed for skincare formulators to calculate complex ingredient ratios, compensate for herbal infusion losses, and receive professional chemical analysis via the Google Gemini AI engine.

✨ Key Features
Smart Ratio Calculation: Automatically adjust ingredient weights based on total batch size.

Herbal Loss Compensation: Input herbal weight and absorption rates to calculate exact oil requirements.

AI Formulation Advisor: Integrates with Google Gemini to provide professional feedback on emulsion stability, skin feel, and preservative safety.

Export Ready: Save your finalized formulas as high-quality JPG or PDF reports for lab records.

Privacy First: No backend server. Your formula data and API keys stay strictly within your browser.

🛡️ Privacy & Security (API Key)
This application uses a "Bring Your Own Key" (BYOK) model. To use the AI analysis features, you must provide your own Google Gemini API Key.

No Data Collection: Your API Key is stored in your browser's localStorage. It is never sent to any server except directly to Google's official API endpoint.

GitHub Safe: This source code contains no hardcoded keys. It is safe to fork, host, and share.

Local Control: You can clear or rotate your API Key at any time using the "Clear API Key" button within the AI interface.

🚀 How to Get Started
1. Get your Free Gemini API Key
Visit Google AI Studio.

Sign in with your Google Account.

Click on "Get API key" and create a new key.

(Optional but Recommended): Set a "Website Restriction" in the Google Cloud Console to your specific GitHub Pages URL to prevent unauthorized use of your key elsewhere.

2. Deployment
You can run this app in two ways:

Local: Simply download the .html file and open it in any modern browser (Chrome, Safari, Edge).

GitHub Pages:

Upload the index.html to a GitHub repository.

Go to Settings > Pages and enable hosting.

Open the provided URL on your iPhone or PC.

3. Usage on iPhone (App-like Experience)
Open your GitHub Pages URL in Safari.

Tap the Share button (square with an up arrow).

Select "Add to Home Screen".

The Lab will now appear as an icon on your home screen and run in full-screen mode.

🧪 Formulation Logic
Q.S. (Quantum Satis): Use the "Auto-Hydrate" button to automatically balance the water phase (the first ingredient) to reach exactly 100%.

Density Support: Input specific gravity (g/ml) for each ingredient to get accurate volume references for lab pipetting.

Safety Check: The system flags errors if your total percentage exceeds or falls short of 100%.

📄 License
This project is for educational and laboratory use. Always perform small-patch testing for any skincare products created.


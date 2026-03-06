# SOC Incident Analysis Tool

A web-based tool designed to assist Security Operations Center (SOC) analysts in analyzing, masking, and reporting on security incidents. This application provides an interface to process security logs, sanitize sensitive configuration data, and generate standardized event analysis reports.

## 🚀 Features

- **Log Analysis**: Input raw security logs for parsing and review.
- **Comprehensive Data Masking**: Automatically detects and aggressively masks over 60 categories of sensitive PII and infrastructure data (including MAC Addresses, UUIDs/Machine GUIDs, Public/Private IPs, Email Addresses, Hostnames, Device IDs, Windows Infrastructure Names, FortiGate VPN fields, cookies, assigned IPs, and metrics) before the text ever touches an AI model.
- **AI-Powered Insights**: (Optional) Integration with AI models to provide automated analysis and summary of the incident logs.
- **Report Generation**: Generates formatted HTML reports suitable for ticketing systems or stakeholder communication.
- **Template-Based Fallback**: Includes standard templates for manual filling if AI analysis is unavailable.

## 🛠️ Technologies Used

- **HTML5**: semantic structure for the application.
- **CSS3**: Custom styling for the dark/light mode interface.
- **JavaScript (ES6+)**: Client-side logic for log processing and masking.

## 📦 Installation & Usage

Since this is a client-side web application, no server installation is required.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/maveera/soc-incident-analysis-tool.git] or Live: https://maveera.github.io/SOC-Incident-Analysis
    cd soc-incident-analysis-tool
    ```

2.  **Run the Application:**
    - Simply open the `Updateindex.html` file in any modern web browser.
    - *Optional*: For a better development experience, you can serve it using a local server (e.g., Live Server in VS Code or Python `http.server`).

    ```bash
    # Example using Python
    python -m http.server 8000
    # Then navigate to http://localhost:8000/Updateindex.html
    ```

## 📖 How to Use

1.  **Paste Logs**: Copy raw text or logs into the designated input area.
2.  **Analyze**: Click the "Analyze" or "Process" button to trigger the masking and analysis logic.
3.  **Review**: Check the output section for the sanitized log and the generated analysis report.
4.  **Export**: Use the "Copy to Clipboard" or "Save Report" button to use the data in your official reports.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1.  Fork the project
2.  Create your feature branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

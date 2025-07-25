# Work Update & Monthly Report Web Application

A mobile-friendly Bootstrap 5 web app that helps users submit work updates via Google Forms and generate monthly PDF reports from uploaded CSV data with dynamic filtering and source data access.

## Features

- Submit work updates through a direct link to a Google Form.
- Download CSV reports exported from Google Sheets.
- Upload CSV files and parse data client-side using PapaParse.
- Dynamically generate month-year filter buttons.
- Generate printable PDF reports with jsPDF and jsPDF AutoTable.
- View the original source data via Google Sheets link.

## Technology Stack

- HTML5, CSS3, JavaScript
- [Bootstrap 5](https://getbootstrap.com/)
- [PapaParse](https://www.papaparse.com/)
- [jsPDF](https://github.com/parallax/jsPDF) & [jsPDF AutoTable](https://github.com/simonbengtsson/jsPDF-AutoTable)

## Usage

1. Open `index.html` in any modern browser (mobile or desktop).
2. Use the **Add Work Update** page to submit updates via Google Form.
3. On the **Generate Report** page:
   - Download and upload the CSV report.
   - Click **Next: Process File** to analyze data.
   - Use the generated month-year buttons to create and download PDF reports.
   - View source data via the dedicated button.

## License

This project is open source and available under the [MIT License](LICENSE).

---

Feel free to edit or extend this README as you develop your project further!

# Carbon Impact Comparison Tool

This project is a **Carbon Impact Comparison Tool** built using **HTML**, **JavaScript**, and **Tailwind CSS**. It helps users compare the environmental impact of websites before and after optimization by analyzing key metrics such as **CO2 emissions per visit**, **energy consumption**, and the number of trees required to offset emissions. Additionally, it generates a case study report based on the comparison, which can be downloaded for future reference.

## Key Features

- **Input Text Comparison**: Users can input raw text from carbon footprint reports of websites before and after optimization.
- **Automatic Metric Extraction**: Automatically extracts key metrics like CO2 emissions, energy consumption, trees offset, and percentile cleanliness.
- **Results Calculation**: Provides percentage decreases in CO2 emissions, energy consumption, and tree offsets between the before and after reports.
- **Case Study Generation**: Generates a structured case study report showcasing the improvements in environmental impact.
- **Downloadable Report**: Users can download the case study as an HTML file.

## Demo

### Before Optimization Example

```plaintext
Website carbon results for: mittlerseniortech.com
Oh no! This web page achieves a carbon rating of F
This is dirtier than 98% of all web pages globally.
Oh my, 5.31 g of CO2 is produced every time someone visits this web page.
10,000 monthly page views, this web page produces 636.96kg of CO2 equivalent.
1662 kWh of energy.
29 trees offset required.
```

### After Optimization Example

```plaintext
Hurrah! This web page achieves a carbon rating of B
This is cleaner than 65% of all web pages globally.
Only 0.32 g of CO2 is produced every time someone visits this web page.
10,000 monthly page views, this web page produces 38.06kg of CO2 equivalent.
99 kWh of energy.
2 trees offset required.
```

### Example Case Study Output

```plaintext
Carbon Impact Case Study

Website Efficiency: Moved from the 2nd percentile (dirtier than 98%) to the 65th percentile (cleaner than 65% of websites).
CO2 Emissions Reduction: 93.97% decrease in CO2 emissions per visit.
Energy Consumption Reduction: 94.04% decrease in energy usage.
Trees Offset Improvement: 93.10% fewer trees needed to offset emissions.

This study showcases the environmental impact of optimizing the website. The significant reductions in CO2 emissions, energy usage, and tree offset requirements contribute to a more sustainable web presence.
```

## How It Works

1. **Input the Reports**: The user pastes the full text of the before and after website carbon reports into the respective input fields.
2. **Extract Metrics**: The tool automatically parses the reports and extracts key metrics, including CO2 emissions, energy consumption, trees offset, and percentile cleanliness.
3. **Calculate the Impact**: The tool calculates the percentage decreases in CO2 emissions, energy consumption, and trees required for offsetting.
4. **Generate the Case Study**: A case study report is generated based on the comparison and can be downloaded as an HTML file.

## Installation

To use the Carbon Impact Comparison Tool:

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/carbon-impact-comparison.git
   ```

2. Open the project folder:
   ```bash
   cd carbon-impact-comparison
   ```

3. Open the `index.html` file in your browser to use the tool.

## Usage

1. Open the project in your browser.
2. Paste the **before** report text into the "Before Optimization" textarea.
3. Paste the **after** report text into the "After Optimization" textarea.
4. Click the **Compare Reports** button to generate comparison results.
5. A case study will be generated based on the results. You can download it as an HTML file by clicking the **Download Case Study** button.

## Technologies Used

- **HTML**: For structuring the page.
- **JavaScript**: For extracting metrics, calculating results, and generating case studies.
- **Tailwind CSS**: For styling the page with a modern, responsive design.
- **Blob API**: For generating and downloading the case study report as an HTML file.

## Future Improvements

- Add support for generating reports in PDF format.
- Allow users to enter custom data (e.g., manual input of CO2 emissions) instead of relying solely on report text.
- Enhance the user interface for better mobile support.
- 
## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests. When contributing to this repository, please first discuss the change you wish to make via an issue.


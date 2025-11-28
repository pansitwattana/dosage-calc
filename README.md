# Rx Kids Calculator - Pediatric Dosage Calculator POC

A lightweight, web-based tool designed to assist in calculating pediatric drug dosages based on body weight. This application is a Proof of Concept (POC) intended for educational and testing purposes.

## Features

- **Weight-based Calculation**: Instantly calculates dosages based on the child's weight in kilograms.
- **Comprehensive Drug Database**: Includes common pediatric medications such as:
  - Paracetamol (Fever/Pain)
  - Ibuprofen (High Fever/Inflammation)
  - Amoxycillin (Antibiotic)
  - And more (CPM, Salbutamol, Domperidone, etc.)
- **Flexible Concentrations**: Supports various drug concentrations (e.g., Syrup 125mg/5ml vs 250mg/5ml).
- **Safety First**: Displays warnings (e.g., "Do not exceed 5 times/day") and category labels.
- **User-Friendly Interface**:
  - Mobile-responsive design.
  - Clear dosage display in both milliliters (ml) and teaspoons.
  - Search functionality to quickly find medications.

## Technologies Used

This project is built as a single-file HTML application for simplicity and portability.

- **React 18**: For UI logic and state management (loaded via CDN).
- **Tailwind CSS**: For modern, responsive styling (loaded via CDN).
- **Font Awesome**: For icons (loaded via CDN).
- **Google Fonts**: Uses 'Sarabun' for typography.

## How to Use

1. **Open the Application**: Simply open the `index.html` file in any modern web browser (Chrome, Safari, Edge, etc.). No installation or server is required.
2. **Enter Weight**: Input the child's weight in kilograms in the top input field.
3. **Select Drug**: Scroll through the list or use the search bar to find the specific medication.
4. **Choose Concentration**: If applicable, select the correct concentration from the dropdown menu to match the medicine bottle you have.
5. **View Dosage**: The calculated dosage will appear on the right side of the card in ml and teaspoons.

## Disclaimer

> **⚠️ WARNING**: This application is a **Proof of Concept (POC)** and is for **testing and educational purposes only**.
>
> - **Clinical verification is required** before administering any medication.
> - Always consult with a qualified pharmacist or physician for accurate dosage instructions.
> - The developers assume no liability for errors or misuse of this tool.

🏠 UiPath Web Data Extraction – Rental Houses in Sholinganallur

📌 Project Overview

This UiPath Studio project automates the process of extracting rental house data from the NoBroker website for the Sholinganallur region. The extracted data is structured and stored in an Excel file for easy analysis and reference.

The automation eliminates manual searching and data entry, improving efficiency and accuracy.

⚙️ Features

      🌐 Automated web scraping from NoBroker

      📍 Filters listings specific to Sholinganallur

      📊 Extracts key property details:

                   House Type

                   Rent Amount

                   Deposit Amount

                   Built-up Area

                   Apartment Type

      📁 Saves extracted data directly into Excel

      🔄 Handles multiple listings dynamically

🛠️ Technologies Used

        UiPath Studio

        Data Scraping Wizard

        Excel Activities

        UI Automation (Selectors)

📂 Project Structure

📁 RentalDataExtraction

│-- Main.xaml              # Main workflow

│-- Output.xlsx           # Extracted data

│-- project.json          # Project configuration

🚀 How It Works

    Launches the NoBroker website

    Navigates to the Sholinganallur rental listings page

    Uses UiPath Data Scraping to extract structured data

    Iterates through multiple pages (if configured)

    Writes extracted data into an Excel file

▶️ How to Run

      Open the project in UiPath Studio

      Ensure all dependencies are installed

      Update selectors if the website layout has changed

      Run Main.xaml

      Check the generated Excel file for output

📊 Output

    The Excel file contains the following columns:

             House Details

             Rent Amount

             Deposit Amount

             Built-up Area

             Apartment Type

⚠️ Notes

    Website structure changes may affect selectors

    Internet connection is required

    Ensure NoBroker access is not blocked

🔮 Future Enhancements

    Add filters (budget, BHK type, furnishing)

    Integrate alerts for new listings

    Store data in a database

    Add scheduling using UiPath Orchestrator

👩‍💻 Author

Sarah Carlyn Jeba.S

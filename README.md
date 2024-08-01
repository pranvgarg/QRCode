# QRCode
# Caffeine Before Chaos QR Code Event Invitation

## Project Description

This project was inspired by an event in our town. We wanted to create QR codes for the attendees to scan upon arrival, allowing us to track attendance and ensure each QR code can only be used once. The system generates QR codes from a provided list of links and maintains a database of attendees who have scanned their codes.

## Files in the Repository

- **QRCode.ipynb**: Jupyter Notebook containing the code to generate and manage QR codes.
- **Links.xlsx**: Excel file with links for generating QR codes.
- **CaffieneDay.png**: Image used for project branding.

## Usage

1. **Generate QR Codes**: The `QRCode.ipynb` notebook will read links from the `Links.xlsx` file and generate corresponding QR codes.
2. **Scan and Validate**: At the event, scan the QR codes to validate attendance and ensure that each code is only used once.

## Getting Started

### Prerequisites

Make sure you have the following installed:
- Python 3.x
- Jupyter Notebook
- pandas
- qrcode

### Installation

Clone the repository:
```sh
git clone https://github.com/yourusername/qr-code-event-invitation.git

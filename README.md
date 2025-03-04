# EuroNormChecker

This project provides an RPA process that checks the Euro standard for a vehicle based on its registration number. By querying the government portal, the process retrieves the Euro emission standard, vehicle details (brand, type, model), fuel type (e.g., gasoline, gas, diesel), and production year.

## Features
- **Input**: Vehicle registration number (provided via queue).
- **Output**: Euro emission standard, vehicle details, and fuel type.
- Fetches data from the official government website for accurate and up-to-date information.

## Requirements
- RPA tool (e.g., UiPath).
- UiPath Orchestrator with an active queue.
- API access to UiPath Orchestrator.

## How to Use
1. Create a Queue in UiPath Orchestrator to hold the vehicle registration numbers.
2. Push the Vehicle Registration Number into the queue using the UiPath API. The RPA process will pick up the registration number from the queue.
3. The process will then fetch the Euro emission standard and other vehicle details from the official government website.
4. **Output**: The retrieved data (Euro emission standard, vehicle details, and fuel type) will be processed and can be stored or further used as required.

## License
This project is licensed under the MIT License.


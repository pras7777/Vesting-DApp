# Vesting Schedule DApp

This DApp allows organizations to create vesting schedules for their tokens and manage stakeholders' access to vested tokens.

## Smart Contracts

1. **OrganizationRegistration.sol**: Manages the registration of organizations and their associated ERC20 tokens.

2. **VestingSchedule.sol**: Handles the vesting schedules for stakeholders, allowing whitelisting and token withdrawal after the vesting period.

## Frontend Pages

1. **Wallet Connection Page**: Users can connect their wallets to interact with the DApp.

2. **Admin Dashboard**: Organization administrators can register their organizations, add stakeholders, and define vesting details.

3. **User Withdrawal Page**: Users can withdraw their tokens if they are whitelisted and the vesting period has elapsed.

## Smart Contract Functionality

- Organizations can register themselves and their ERC20 tokens.
- Admins can add stakeholders and define vesting schedules for each type of stakeholder.
- Whitelisted addresses can claim their tokens after the vesting period.
- Only organization admins can withdraw tokens on behalf of stakeholders.

## Frontend Interaction

1. **Wallet Connection**: Users need to connect their wallets using a supported wallet provider like MetaMask.
2. **Admin Registration**: Admins can register their organizations, add stakeholders, and define vesting details.
3. **User Withdrawal**: Whitelisted users can withdraw their vested tokens from the DApp interface.

## Readme File

The README.md file provides detailed instructions on how to use the DApp, including:

- Installation instructions for setting up the DApp locally.
- Usage guidelines for interacting with the DApp.
- Dependencies and requirements.
- Contribution guidelines for developers interested in contributing to the project.
- License information.

The README.md file ensures that users and developers can easily understand and use the DApp.

## Getting Started

To get started with the DApp, follow these steps:

1. Clone the repository to your local machine.
2. Install dependencies using `npm install`.
3. Start the local development server using `npm start`.
4. Connect your wallet to interact with the DApp.
5. Admins can register organizations and manage stakeholder vesting schedules.
6. Whitelisted users can withdraw their vested tokens.

## Contribution

Contributions to the project are welcome! If you encounter any issues or have suggestions for improvement, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). Feel free to use and modify the code for your own purposes.


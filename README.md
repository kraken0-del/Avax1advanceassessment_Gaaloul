### Defi Empire

#### `transfer`

- **Description**: Transfers a specified amount of tokens from the sender's account to the recipient's account.
- **Function Signature**: `function transfer(address recipient, uint amount) external returns (bool)`

#### `approve`

- **Description**: Allows the spender to withdraw from the sender's account, multiple times, up to the specified amount.
- **Function Signature**: `function approve(address spender, uint amount) external returns (bool)`

#### `mint`

- **Description**: Mints a specified amount of tokens and assigns them to the sender's account.
- **Function Signature**: `function mint(uint amount) external`

#### `burn`

- **Description**: Burns a specified amount of tokens from the sender's account.
- **Function Signature**: `function burn(uint amount) external`

#### `transferFrom`

- **Description**: Transfers a specified amount of tokens from the sender's account to the recipient's account, provided the sender has been approved to do so.
- **Function Signature**: `function transferFrom(address sender, address recipient, uint amount) external returns (bool)`

### Vault

#### `deposit`

- **Description**: Deposits a specified amount of tokens into the vault and mints corresponding shares to the depositor.
- **Function Signature**: `function deposit(uint _amount) external`

#### `withdraw`

- **Description**: Withdraws a specified amount of shares from the vault and burns the corresponding shares, transferring the equivalent tokens to the withdrawer.
- **Function Signature**: `function withdraw(uint _shares) external

## Author

Amir Gaaloul 

202010735

https://github.com/kraken0-del

## License

This project is licensed under the MIT License - see the LICENSE file for details

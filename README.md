# Blockchain-for-supply-chain-Management

## Project Overview

Blockchain for Supply Chain Management is a Java-based application designed to improve transparency, security, and traceability in supply chain operations.

The project uses blockchain technology to store product transaction records in blocks connected through cryptographic hashes.

It provides a graphical user interface (GUI) to manage products and verify blockchain integrity.

## Features

- Add new products to the supply chain.
- Store product transaction details.
- Generate unique SHA-256 cryptographic hashes.
- Maintain previous block hash connections.
- Validate blockchain integrity.
- View blockchain transaction details.
- Clear product records from the GUI table.
- User-friendly Java Swing interface.

## Technologies Used

- Java (JDK 21)
- Java Swing (GUI)
- Object-Oriented Programming
- Blockchain Technology
- SHA-256 Hashing
- VS Code

## Project Structure

```text
BlockchainSupplyChain/
│
└── src/
    ├── blockchain/
    │   ├── Block.java
    │   └── Blockchain.java
    │
    ├── gui/
    │   └── SupplyChainGUI.java
    │
    ├── model/
    │   └── Product.java
    │
    └── Main.java
```

## Requirements

- Java Development Kit (JDK 21 or above)
- Visual Studio Code (optional)
- Windows/Linux operating system

## How to Run

**Step 1:** Download or clone this repository.

**Step 2:** Open the project folder in VS Code.

**Step 3:** Open the terminal and navigate to the `src` folder.

```bash
cd src
```

**Step 4:** Compile the Java files.

```powershell
javac -d . (Get-ChildItem -Recurse -Filter *.java | ForEach-Object FullName)
```

**Step 5:** Run the application.

```bash
java gui.SupplyChainGUI
```

## How It Works

1. The user opens the Supply Chain Management application.
2. Product details are entered through the GUI.
3. A new block is created containing product transaction information.
4. SHA-256 generates a cryptographic hash for the block.
5. Each block maintains a connection with the previous block.
6. The user can validate the blockchain to check its integrity.

## Expected Output

The application displays a graphical interface containing:

- Product ID
- Product Name
- Sender
- Receiver
- Quantity
- Status
- Block Hash

Users can add products, validate the blockchain, view blockchain details, and clear the table.

## Future Enhancements

- Database integration for permanent storage.
- User authentication and access control.
- Smart contract integration.
- Real-time supply chain tracking.
- Web-based application support.

## Author

**MD Jaid Jamil**

## License

This project is developed for educational purposes.

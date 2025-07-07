# Simple Auction System 💸

This is a Python console application that simulates a basic auction system using object-oriented programming principles.  
I built this project to deepen my understanding of Python, especially how to design and work with multiple interacting classes.

---
## About the Files 🗂️

- **`auction.py`**  
  This file has the main classes that power the auction system — like `Auction`, `Lot`, `Bid`, and `Person`. It’s where the logic lives: how bids work, how lots are tracked, and how people place bids.

- **`auctionsystem.py`**  
  This is the program you actually run. It uses the classes from `auction.py` to let you interact with the auction through a simple menu. You can add items, bid on them, see the highest bids, and save everything to a file.

Basically, `auction.py` is the engine, and `auctionsystem.py` is the driver that makes it all happen for you in the terminal.


## 📌 What it does

The system models a simple auction where users can:

- **Add new items (lots)** with descriptions to the auction.
- **List all items** currently available for bidding.
- **Place bids** on items, with checks to ensure bids are higher than previous ones and within auction time limits.
- **View the highest current bid** for any item.
- **Save and load auction items** to and from a text file, allowing the auction to persist across sessions.

The core of the system is built around four classes:

- `Auction` — manages the collection of auction items and bidding process.
- `Lot` — represents an individual auction item, tracking its bids, reserve value, and auction duration.
- `Bid` — encapsulates details of a single bid including bidder and amount.
- `Person` — represents a bidder with a name.

## 💡 Why I built this
I created this project to practice fundamental Python concepts including:

Writing and organizing code using classes and objects.
Implementing file input/output for data persistence.
Designing a user-friendly console interface for interaction.
Applying basic logic for auction rules like bid validation and auction timing.

This project helped me solidify how multiple classes can work together to build a functioning system.

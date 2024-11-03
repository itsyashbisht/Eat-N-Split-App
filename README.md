# Eat-N-Split

Eat-N-Split is a React application designed to help friends keep track of shared expenses and split bills with ease. Users can add friends, select a friend, enter shared expenses, and calculate who owes whom. Ideal for group outings, shared accommodations, or any situation where expenses need to be split fairly.

## Features
- **Add New Friends**: Add friends with name and profile picture.
- **Track Balances**: View each friend’s balance to know if they owe or are owed.
- **Split Bills**: Enter bill details and choose who paid, updating balances automatically.
- **Responsive UI**: Simple and responsive interface for easy use across devices.

## Installation and Setup
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/itsyashbisht/Eat-N-Split.git
   cd Eat-N-Split

# Usage Guide

1. **Add Friends**: Click "Add Friend," enter a name and image URL, and save.
2. **Select a Friend**: Choose a friend from the list to view or manage balances.
3. **Split Bills**: Enter the total bill and specify how much each person paid. The app will update the balance based on the input.

# Project Structure

The app is divided into the following components:

- **App**: Manages application state and renders main components.
- **FriendsList**: Lists all friends and their balances.
- **Friend**: Displays individual friend details and balance.
- **FormAddFriend**: Form to add new friends.
- **FormSplitBill**: Form for splitting the bill between the user and the selected friend.


# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

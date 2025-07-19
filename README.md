# 🗳️ VoteChain – Blockchain-Based Voting System

> A secure, tamper-proof, and visually interactive blockchain-based voting simulator built with Python, Gradio, and real-time analytics.

---

## 📌 Overview

**VoteChain** is a Python-powered simulation of a modern voting system that uses blockchain technology to ensure vote transparency, prevent tampering, and visualize election outcomes. It provides voters with a simple interface while offering administrators tools for monitoring, analysis, and fraud detection.

This project showcases concepts from **blockchain**, **data science**, **visual analytics**, and **cybersecurity**, making it ideal for academic portfolios and technical demonstrations.

---

## 🚀 Key Features

- 🔐 **Blockchain-based voting** with SHA-256 integrity
- 🧠 **One voter, one vote** logic with identity hashing
- 📊 **Live results** using Pie and Bar charts (Plotly)
- 📅 **Vote timeline chart** using Matplotlib
- 📉 **Vote fraud detection** (spike pattern analysis)
- 🛠️ **Admin dashboard** for ledger monitoring
- 📁 **CSV export** with full vote + summary report
- 🌐 **Gradio GUI** for user-friendly interaction

---

## 🎯 How It Works

1. Voter submits a unique ID and selects a candidate.
2. The system hashes the ID and checks for duplicates.
3. If valid, a new block is created and linked to the blockchain.
4. The vote is recorded with timestamp and hashed linkage.
5. Live visualizations update with every new vote.
6. Admin can monitor blockchain and download logs.

---

## 🖥️ Tech Stack

| Tool           | Purpose                                |
|--------------- |----------------------------------------|
| **Python**     | Core programming language              |
| **Gradio**     | GUI for interaction                    |
| **Plotly**     | Live bar and pie chart visualizations  |
| **Matplotlib** | Vote timeline chart                    |
| **Pandas**     | Data handling & CSV export             |
| **Hashlib**    | SHA-256 for secure voter ID hashing    |



## ⚙️ Installation

### 🔧 Requirements

Install required packages:

pip install gradio pandas matplotlib plotly

import gradio as gr
paste the full code and run app.launch()

**License:** This project is licensed for educational and non-commercial use. Feel free to fork and build upon it!

# Binary Risk v2

A lightweight, modernized tool for assessing information security risk levels following the Binary Risk Analysis methodology created by [Ben Sapiro](https://binary.protect.io/).

## About the Application

This web application provides a streamlined implementation of Binary Risk Analysis, a process for evaluating information security risk. The original app was developed by Ben Sapiro in 2011. This updated version preserves Ben's documented methodology while using simpler code and rendering correctly in modern browsers

- **Adheres to Binary Risk Analysis methodology** as documented by Ben Sapiro.
- **Works in modern browsers**
- **Has shareable URLs** for saving and revisiting assessment results.

Additionally, this app is implemented in a single, framework-free static HTML file. This makes it easy to understand, modify, and deploy.

## About Binary Risk Analysis

Binary Risk Analysis (BinRA) is designed to structure subjective conversations about risk levels. Its simplicity allows it to be applied efficiently across all items in a risk register, enhancing communication between security and business teams.

The original description of Binary Risk Analysis can be found [here](https://binary.protect.io/).

Additional discussions and resources related to Binary Risk Analysis include:

- [A post by Adam Shostack on Binary Risk Analysis](https://shostack.org/archive/2011/10/some-thoughts-on-binary-risk-analysis/)
- [A Minimum Viable Information Risk Management Program (PDF)](https://static1.squarespace.com/static/6128b1eb2eb2cf15b7a35a2f/t/618a3d48035a0148aae29593/1636449609423/Minimum_Viable_Information_Risk_Management_Program.pdf)
- [Initial Steps Towards A Risk Management Plan: Creating a Basic Risk Register](https://www.leviathansecurity.com/blog/initial-steps-towards-a-risk-management-plan-creating-a-basic-risk-register)
- [Another version of the BinRA web app by jerryjvl](https://github.com/jerryjvl/binary)

## Licensing

The Binary Risk Analysis methodology was released under a Creative Commons license, and the original app code is licensed under GPLv3. This version, which adapts Ben's original code, is also distributed under the GNU General Public License v3.

Binary Risk Analysis v2 Copyright (C) 2024 by Brian Myers

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see https://www.gnu.org/licenses/.

## Accessibility

This app includes basic ARIA tags to support accessibility. Contributions to improve ARIA support are welcome, especially from those with more experience in accessible design.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/SafetyLight/BinaryRisk.git

2. Open `BinaryRisk.html` in your preferred browser to begin assessing risks.

3. To modify or extend the tool, edit the HTML file directly. No additional dependencies or build steps are required.
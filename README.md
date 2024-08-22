# WEB102 Prework - *Sea Monster*

Submitted by: **Kristal Hong**

**Sea Monster** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: **15** hours spent in total

## Required Features

The following **required** functionality is completed:

* [x] The introduction section explains the background of the company and how many games remain unfunded.
* [x] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [x] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [x] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [x] Added search functionality that involves creating a search bar and filtering the list of games based on user input.

## Video Walkthrough

Here's a walkthrough of implemented features:

<img src='http://i.imgur.com/link/to/your/gif/file.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />
![SeaMonsterCrowdfundingProject](https://github.com/user-attachments/assets/ec5d6e41-9ff4-43b2-ad39-41d2346867dc)


<!-- Replace this with whatever GIF tool you used! -->
GIF created with [Kap](https://getkap.co/)
<!-- Recommended tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

**Challenges**:
* Managing Dynamic Content Updates: Updating the list of games based on filter buttons (unfunded, funded, and all games) posed challenges in terms of efficiently manipulating the DOM. I needed to ensure that the game list updated without unnecessary re-rendering or performance issues, which involved optimizing the filtering logic and ensuring smooth transitions between different game views.
* Debugging the Search Functionality: Implementing the search feature involved several challenges, such as ensuring that the search bar correctly filters games based on user input. This required managing the state of the input field and  updating the displayed games. I had to carefully test different edge cases to ensure that the search function handled cases like partial matches and case sensitivity correctly.

## License

    Copyright [2024] Kristal Hong

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

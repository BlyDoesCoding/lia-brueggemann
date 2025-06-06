---
title: 'Watson'
slug: 'watson'
summary: 'Watson is a Discord Activity setter written in Go and Fyne. Its rather simple to use and can come in Handy. You can mainly use it for having Custom Status Messages to show your Friends what you are doing.' # This is what will be displayed as summary for the post (the theme will automatically generate one from the content you write in the post if left empty)
description: # This is what will be displayed as meta data (the theme will automatically grab it from summary if left empty)
date: '2023-11-03T11:16:02+02:00'
expiryDate: '' # You want your post to vanish after a certain date? Write it down here! Must be in the same format of `date`
translationKey: watson # If you have a translated post for this one, set the same translationKey to have the translation displayed
layout: 'single'
version: '1.0.0' # <--- Add this line
source: "https://github.com/BlyDoesCoding/Watson"
releases: "https://github.com/BlyDoesCoding/Watson/releases"
languages:
  - go

platforms: # <--- New parameter
  - Windows
  - Linux
  - macOS
license: "BSD 3-Clause" # <--- Add this line
---


Watson is a Go program that integrates with Discord's Rich Presence (RPC) feature to display various information on your Discord activity. Whether you want to showcase the book you're reading, indicate when you're in a conversation, browsing a website, streaming, or providing a link to your stream, Watson offers a versatile way to personalize your Discord presence.

## Table of Contents

- [Installation](#installation)
- [Features](#features)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Installation

You can find the latest release of Watson on the [Releases](https://github.com/BlyDoesCoding/Watson/releases) page. Download the binary executable for your platform.

## Features

- Customize your Discord activity with rich presence information.
- Show the book you are currently reading.
- Indicate when you are in a conversation.
- Display your browsing activity on a specific website.
- Show when you are streaming and provide a link to your stream.
- Lightweight and easy-to-use Go program.

## Usage

1. Download and install Watson following the installation instructions.
2. Customize your rich presence activity to include details about the book you're reading, conversations, websites, and streaming.

## Contributing

Contributions to Watson are welcome! If you'd like to contribute to this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and test them thoroughly.
4. Submit a pull request, describing your changes in detail.

## License

This project is licensed under the [BSD 3-Clause License](LICENSE). See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to the Discord community for their support and resources.
- This project relies on the [rich-go](https://github.com/hugolgst/rich-go) library by [hugolgst](https://github.com/hugolgst) for Discord Rich Presence integration.

Enhance your Discord presence with Watson and share your activities, books, conversations, and streams with your friends!
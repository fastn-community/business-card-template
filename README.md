# Business Card One Template using `fastn`

This repository provides a prototype to create customizable business card 
design using the `fastn` language. You can create designs which can be used 
by users to easily create professional business card by filling in their 
information.


## Getting Started

To use this template, follow the steps below:

1. Click on `Use this Template` or go to the following [link](https://github.com/new?template_name=business-card-1-template&template_owner=fastn-community)
2. Enter the required details to create new repository.
3. Clone this newly created repository to your local machine.
4. Open the `fastn` file named `index.ftd` in a text editor.

## Creating a new Business Card category

The `index.ftd` file contains placeholders that you can replace with your own information. Here's what you need to do:

### 1. Replace Package Information

In the section labeled "DOCUMENTATION FOR YOUR CARD COMPONENTS", locate the 
`docs.home-card` component and check the following placeholders:
**Note:** These all are auto-filled values during repository creation

- `package-name`: Your repository name
- `package-full-name`: Your GitHub repository's full URL
- `license-url`: URL to the license of your choice (e.g., MIT License)
- `github`: Your GitHub Repository URL

### 2. Implement Front and Back Components

In the same "DEFINE YOUR CARD COMPONENTS" section, you will find placeholders for implementing the front and back components of your business card.

For the front component (`front`), you need to use the following headers 
(card details):
**Note:** These headers will be used by the users for filling in their 
information. It's mandatory to use all these headers while creating your 
component.

- `caption name`: You name (e.g., "John Doe")
- `string title`: Your job title
- `string company`: Your company name
- `ftd.image-src logo`: Image asset or Image URL to your company logo
- `contact-1`: Your primary contact number (Optional for user)
- `contact-2`: Your secondary contact number (Optional for user)
- `website-1`: Your email or social media link (Optional for user)
- `website-2`: Your email or social media link (Optional for user)
- `location`: Your address

For the back component (`back`), you can provide:

- `string company`: Your company name
- `ftd.image-src logo`: Image asset or Image URL to your company logo


Remove the comments (i.e. Replace `/--` with `--`) and replace `;; <YOUR 
IMPLEMENTATION HERE>` with your actual component implementation/definition 

***Important***: After implementing `front` and `back` components in 
`index.ftd`, uncomment `category` header in 
- `docs.home-card` (index.ftd)
- `docs.how-to-use-card` (docs/card.ftd)
- `docs.how-to-use-card-back` (docs/card-back.ftd)

## Some other information:

The sitemap present in `FASTN.ftd` is used to organise your package. 
This uses 

- `index.ftd`: It is the homepage which shows preview of front and back for 
  your card
- `docs/card.ftd`: It shows how to use `front` component of card.
- `docs/card-back.ftd`: It shows how to use `back` component of card,

The documentation for this template comes from [`business-card-1`](fastn-community.github.io/business-card-1)

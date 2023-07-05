# Bocconilib: Get instant access to journal articles though Bocconi's library

[Bocconilib](https://jlopezton.github.io/bocconilib/) is a convenient tool for Bocconi University personnel, specifically designed to streamline access to restricted journal articles via the Bocconi Library's off-campus website. The process involves converting standard journal article URLs into ones that are compatible with Bocconi Library's system, thereby allowing users to directly access articles through the library's service.

## What does it solve?

Typically, when you find a journal article that's locked behind a paywall or otherwise restricted, you would need to access it through the Bocconi Library's off-campus website. This entails navigating to the library website, finding the specific journal, and then conducting another search for the desired article. The entire process needs to be repeated for each article, resulting in significant time wasted on redundant searching. 

Bocconilib effectively eliminates these extra steps, allowing you to directly access these articles in just one click. 

## How does it work?

Bocconilib simplifies URL conversion into a more user-friendly process. It achieves this by adding the URL hostname of the original journal at the beginning of the library website address, replacing dots (.) with dashes (-), and prefixing the entire string with an "0-". This formatted URL signals to the journal website that you're accessing it through the library, hence, granting you access to the content.

## Example Usage

Consider an instance where you find an intriguing article about [Poverty and Crime in the British Journal of Sociology](https://onlinelibrary.wiley.com/doi/full/10.1111/1468-4446.12083) (published by Wiley). Without being on campus, your access to the article would be restricted. 

Typically, to bypass this, you would need to navigate to the Bocconi Library website, search for BJS, open the relevant link, log in with your Bocconi credentials, and search again for the original article. Only after all these steps would you finally gain access to the desired content. 

Bocconilib drastically simplifies this process: all you need to do is copy the original article URL and convert it using the program. The [resulting link]() will grant you access through the Bocconi Library. Although you might still be asked to enter your Bocconi credentials, this method saves you the hassle of searching for the journal and article manually each time.

# bocconilib
Converts Journal Links into Bocconi Library links that have full article access (Only works for Bocconi personnel).

When you find an article for which you don't have access, you can use the library's off-campus website to access it. 

This very simple program coverts a URL for a journal article in a URL that uses Bocconi Library as a passthrough. This allows users to see articles for which Bocconi has access.
Generally, users that are working outside of the university can have access to articles as if they were on campus, by going into the library website, looking for the journal and then searching for the article. This must be done for each article, meaning time lost doing two searches.
This program allows users to have direct access to articles without going to the Bocconi Library website, looking for the Journal and then looking again for the article. The converted URL is already in the format that allows the journal to ‘understand’ that you are using the library.
The conversion is actually very simple: To get the Bocconi library link, the url hostname of the journal is added at the beginning of the library website (lib.unibocconi.it), but with dashes (-) instead of dots (.) and with an additional "0-" at the beginning.

Example 1: You find an article about Poverty and Crime. The article is in British Journal of Sociology, which is part of Wiley Publishing. Your access will be restricted if you're not on campus. If you want to use Bocconi Library’s off campus access, you will go to the Bocconi Library website, search for BJS, open the link, log in with your Bocconi credentials, search for the article again, and just then you would access to the article.
The program simplifies things by allowing you to just copy the article URL, then get a link that has access through Bocconi library, saving you a few steps.
 And clicking the new URL link. Bocconi may ask you for your credentials, but you save the time of doing the search of the journal.

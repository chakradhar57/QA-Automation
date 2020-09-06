# QA Engineer Assessment Solution

## Introduction

Name:Chakradhar Papanaboina


I successfully installed the  v12 node version and i checked for the version
PS F:\qa-test-assessment-master> node -v
v12.18.3
i installed the vs code the app is working  fine on the node 12 version.
when i ran ng serve initially i had seen errors i resolved thoose errors by installing
1)npm install
2)npm install --save-dev cucumber protractor-cucumber-framework chai @types/chai @types/cucumber
3)npm install -f protractor
4)npm install @angular-devkit/build-angular@0.13.0
5)npm install -g protractor
6)I added frameworkPath: require.resolve('protractor-cucumber-framework') in protractor.config

after that i was able to configure the envorinment in my system then i ran ng serve and i navigated to localhost:4200
Then i ran ng e2e
The existing test case ran successfully
1)## Search for character (person)
*	When you search for **a character** and it’s a valid one, then you should be able to see his / her “Gender”, “Birth year”, “Eye color” and “Skin color”.
*	When you search for a character and it’s not a valid one, then you should be able to see “Not found” in the results.
        ans:I ran this testcase i got an error in my terminal but at browse level the test case went successfully i attached the screenshot in screenshots folder.
2)### Search for planet
*	When you search for **a planet** and it’s a valid one, then you should be able to see its “Population”, “Climate” and “Gravity”.
*	When you search for a planet and it’s not a valid one, then you should be able to see “Not found” in the results.
        ans:i changed the defaultsearchtype to 'planets' in search-form.component.ts,I ran this testcase i got an error in my terminal but at browse level the test case went successfully i attached the screenshot in screenshots folder.
3)### Additional flows
*	When you search for either a character or a planet and you get one or more results for it, clear the “Search form” and hit the Search button again, you should then get an empty result list (previous search results are removed).
*	You can search for results by clicking the “Search” button or by pressing “enter” on the search field.
*	When for example you have searched for a full planet name and you’ve got results, if you switch to People and search for the same thing (that has no matching people based on a partial name), you should get a “Not found” in the results.
*	You can have more than one results, for both Planets and Names (partial matching)
I was able to search the character and clear the search from and when i hit search button the search results still showing the previous one, and also i am not able switch to radio button since the default type was set to people.
The app is working fine in every given scenerio expect the when search the character and clear the search from and when i hit search button the search results still showing the previously searched one.




## Remarks 

...

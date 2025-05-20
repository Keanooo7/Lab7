
# Check For Understanding:
1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.
 
  - ( Within a Github action that runs whenever code is pushed ) 
  - Manually run them locally before pushing code
  - Run them all after all development is completed

I would integrate my end‑to‑end tests within a GitHub Action, This is because it gives me immediate, continuous feedback on whether a change breaks the main brachs existing functionality. these tests would also provide better visibility to my teamates on my testing. 
 
2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)

No, this is because you’d want to use a unit test for that, not an end‑to‑end test.

3) What is the difference between navigation and snapshot mode?
Navigation mode analyzes the complete page loading process from start to finish, measuring metrics like First Contentful Paint, Largest Contentful Paint, Total Blocking Time, and Speed Index. where as Snapshot Mode will only analyze the current state of the page at the moment you ran the test not the enute loading proccess. Also instead of providing metrixes like the Navigation mode Snapshot mode focuses more on the current DOM state for issues like accessibility. 

4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
 1) Image Optimization, the report stated that there porrly sized images in our site "Properly size images Potential savings of 518 KiB" this means that properly sizing our images could provide a 518 KIP boost to performance. It had also recomended "Serve images in next-gen formats Potential savings of 165 KiB". if both of these are done we could reduce bandwidth usage, improve loading times, and could further enhance the already good Performance score of 99

 2)Add Proper Viewport Meta Tag: throughout the report we see 2 report flags stating that "Does not have a <meta name="viewport"> tag with width or initial-scaleNo `<meta name="viewport">` tag found", Adding this tag is would help improve responsive design and proper display on mobile devices. 

 3) Internationalization and localization: The report also states that "<html> element does not have a [lang] attribute" this means that if the page isn't actually in the default language, then the screen reader might not announce the page's text correctly. Fixing this would improve the interpretation of your content by users in different locales.


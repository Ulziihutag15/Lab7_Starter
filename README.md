# Ulziikhutag Davaasuren

1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.  

Answer: Within a Github action that runs whenever code is pushed.  

Explanation: Running automated tests through GitHub Actions ensures continuous integration with consisten and automatic testing.  

2) Would you use an end to end test to check if a function is returning the correct output? 

Answer: No.  

3) What is the difference between navigation and snapshot mode?  

Answer:  
Navigation mode analyzes the initial state of a page right after it loads. While, Snapshot mode analyzes the current state of a page, possibly after some modifications from the initial state. These two can differ in performance results depending on how the website handled the interactions from initial to the current state.  

4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.  

Lighthouse results reported the following issues:  
* Images were larger than their displayed size. Thus, smaller image could be used to save cellular data and faster loading time.  
* It was missing (meta name="viewport). Including it would have ensured better fitting for mobile screen sizes, and preventing a 300 millisecond delay to user inputs.  
* (html) element does not have a [lang] attribute. We can add the [lang] attribute to ensure screen readers use the correct language to display the correct texts in the webpage.  

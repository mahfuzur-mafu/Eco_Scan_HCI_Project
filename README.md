# Eco_Scan_HCI_Project
When newcomers or sometimes locals in Finland try to dispose of trash, they often face confusion about where specific items belong. Everyday items, like chips packets or coffee cups with leftover liquid, don’t always fit neatly into one category, leading to uncertainty about whether they should go in plastic, paper, mixed, polyethylene trash, or another specific bin. This confusion can be frustrating and may result in incorrect sorting, which contaminates recycling streams and lowers recycling efficiency. Finland has achieved the EU’s ambitious landfill goal, with only 1% of municipal waste ending up in landfills compared to the EU target of 10% or less. However, Finland is currently behind the EU recycling targets, recycling about 42% of municipal waste, short of the 55% target by 2025. This shortage is partly due to wrong waste sorting, which affects recycling rates and increases the reliance on waste-to-energy incineration. Around 53% of municipal waste is incinerated for energy, a process that, while reducing landfill use, contributes to carbon emissions.

I propose a mobile application that can, by scanning an item in real time, instruct on how to sort out waste. An image recognition scanning method for the different types of waste will automatically detect and direct users to the appropriate bin for disposal. By offering simple, easy-to-follow instructions in the sorting of waste, this application would reduce confusion and greatly increase the accuracy of appropriate waste disposal.

The user requirements from Part 2 are as follows: "The application would be simple and easy to use, especially for beginners. It would also include either built-in translation support or an English-language option to take into account both locals and international residents. By leveraging mobile technology, the app would provide a portable solution to waste sorting confusion. This could contribute to better recycling rates, less contamination, and easier waste sorting for everyone in Finland, regardless of experience with the system."

Iteration 01 

Goal: 

This first iteration was meant to outline the basic structure of the application and the flow of navigation. More precisely, I wanted to learn about how users expect to interact with the application and what functionality they believe is essential to include. Among my research questions during this stage included the following:

1. What are the features that the application needs to focus on?
2. How do users expect to interact with the app for its core functionalities-scanning and viewing      
    sorting instructions?
3. Are the initial layout and navigation intuitive for users?
These questions were selected because they give the basic insights into user expectations to avoid unnecessary complexity and ensure user-centered design. This helps to avoid further problems that could arise with usability later in the development process.

The prototype:
 Low-Fidelity Prototype

In this iteration, I used a Low-Fidelity Prototype as wireframes to construct the first point in the design process. The wireframes helped in outlining the basic structure and navigation of the app while letting one visualize how the design might look. This was done because wireframes are quick to make, easy to change, and flexibility is allowed in iterative improvement from user feedback.
1. Home Screen: On the home screen, the user can change the preferred language of the app. Apart from this, there will be a picture or demo to show the user how to scan items for waste sorting.
2. Scanning Interface: The scanning interface will feature the camera to capture the picture of the item the user intends to sort; alternatively, they can upload a picture they have already taken.
3. Results Page: Scanned or uploaded picture of the detected item with its appropriate waste bin category.
4. Category of Trash Container: This section will hold information related to different categories of trash, guiding users on where to dispose of their waste. It will also include a description of each category to clarify the sorting process.
5. The Details about Trash Container: Under each type of trash category, there will appear the summary-for instance, what should be sorted into this container and what is forbidden to dispose of there. 

<img width="470" alt="image" src="https://github.com/user-attachments/assets/6deb6523-2a79-45bb-b81c-f1a1bf8c4e3c" />

 
Figure: Iteration 1 Layout

Method:
I have chosen the semi-structured interview method since it contains a balance of structured questions with freedom that allows participants to express themselves in depth about their thoughts and experiences. In this interview, I chose one of my flat mates who is Finnish since he will be in a better position to guide me through as a native to provide rich insights into the design. I prepared a set of interview questions, conducted an interview, and recorded his feedback. In this way, I could collect both quantitative insights and qualitative feedback to improve the design of the app.
Result: 
The evaluation from the semi-structured interviews provided rich information on the user experience and guided the areas of improvement that needed to be addressed in the design of the app. Below is the conversation of my conducted interview
1. What do you think this app does based on the wireframe?
He understood the main functionality of the app-waste sorting through item scanning-but mentioned not being clear about how a user would tell if the page were actually processing or it is just hanging in there. He pointed out there was no progress bar to let the user know the scan had completed, a very valid point for clarity and usability.
2.Are the instructions to scan clear?
The instructions were simple, yet he said they should be more specific. He suggested putting an example image to illustrate precisely how the scanning process works, like how a user should hold the item being scanned for the camera. This suggests clear, actionable instructions are necessary.
3.How natural is navigating between the screens?
He recognized that the app was in the Low-Fidelity Prototype stage and suggested adding real-world application-like buttons to improve navigation. This feedback points to a need for a more realistic design, especially in terms of user interaction elements.
4.What do you feel is missing or could be improved in this design?
He suggests including a quick guide that explains what each type of waste bin is and making the scanning instructions much clearer on the homepage and the scanning page. Such feedback would say that the application needs better onboarding, especially for new users, in order for easier and smoother navigation.
From the interviews, some common themes I heard were in the clarity of instructions, intuitive navigation, and user-friendly through attractive design. These data suggested that the essence of the app was clear, but refinement of design elements such as navigation and instructions is needed. It also emphasized how the instructions should be clearer and more specific; the visual layout and flow of navigation also needed an upgrade. These are some of the changes that will help in enhancing usability by building user confidence for better and smooth experiences while working on the app.
Iteration 02 
Goal
The major activities of this iteration are the refinements of the prototype based on feedback that was collected from Iteration 1-specifically, problems with usability and instruction clarity, and the ease of use in terms of navigation.
This is the research question that I chose for this iteration
1. How well does the improved prototype address usability issues identified from Iteration          
    problems with progress indicator clarity and navigation?
2. Are the new instructions clearer and more helpful to the users in particular for scanning an    
    waste sorting?
3. Is the instructional material and scanning feature easier to use and clearer than before?
I choose these question because, these question can also help in understanding whether the changes made to the application address usability issues identified during Iteration 1 and meet the user's expectations. These served as guidelines in further refinement of the prototype, concerning the improvement of the general flow, intuitive, and clear functioning of the application for the targeted users.
The Prototype:
High Fidelity Prototype

This prototype model is selected because it incorporates more realistic elements of the application in it, including the progress bar, ease of navigation, and better instruction material. This will let users interact with the app in its most complete setting and give a good feeling for what their experience will be in naturalistic conditions.
The refined high-fidelity prototype incorporates some key changes and improvements:
1. Home Screen: The language change-over feature is more accessible and much more prominent. Further, an image has been added showing how to scan items to help give clearer instructions for users on using the scanning functionality.
2. Scanning Interface: A new progress bar has been integrated into the scanning interface to let users easily track the status of the scan. This is an implementation of the feedback from Iteration 1, where the users did not know if the scanning process was in progress or not.
3. Results Page: The results page now displays waste categories more clearly, with additional information to help users understand which bin their item goes into. 
4. Trash Category Materials: A quick guide explaining the different categories of wastes has been made more prominent and accessible. This will help users understand the process of sorting wastes, hence furthering the educational aspect of the app.
5. Navigation: Now, navigation in this app is further cleaned up-labelling made much easier and clearer, and laying out. This definitely will make one's switch and toggling between different pages or functions quite facile.


<img width="468" alt="image" src="https://github.com/user-attachments/assets/75081486-cd3d-4103-a323-e6133bf1476e" />

 
Figure: Iteration 2 Layout
Method:
In this iteration, I chose the evaluation method as Google Form Survey. The survey contained quantitative questions (rating) and qualitative questions regarding suggestions on key aspects of usability and user satisfaction. Because it can offer quick, structured feedback from a wide range of users; hence, this can be an effective way to gain various insights. The survey format makes it very easy to analyze and compare responses, which also allows for both numerical ratings and qualitative, in-depth feedback. The survey questions and answers are as follows:
Result:

      
   
   
![image](https://github.com/user-attachments/assets/f181f6fa-9768-4ab7-b1fa-11a28e357a12)

   
   
From the responses to the survey, it could be induced that all the features of the app pleased its users. Waste sorting instructions and the navigation scored perfectly at 5.00/5.00, evidencing that users found them clear and effective. Scanning reached an average of 4.60/5.00, which means most expectations concerning this feature were met but always allows room for improvement. Color and layout scored perfectly at 5.00/5.00, showing that it was visually appealing for the users. The educational material regarding waste categories was well received; it scored a perfect 5.00/5.00, confirming that users found this information very useful and helpful. This depicts overall positive feedback. But then again, these ratings build a platform upon which further development of the user experience can proceed.

After analyzing responses, the improvement of the Discovery Page by adding a picture or an icon of the trash box, along with a title and description, to make it more informative in a visual sense. The second point concerned the Back Button, where users felt that the label "Back" should be removed and only the icon retained, as they found the label confusing. Further, it was pointed out that such buttons needed to be designed consistently, and if possible, the label and icon should both be retained on the button to give it a more harmonious look and feel. The optimization of the Language Change could be made by making it a split button; there's no point in having to click twice to change the language. Just some of the suggestions that came out to help make the interface of the app more streamlined and usable were as follows.


The survey results indicated that the changes in this iteration worked well and improved the user experience in this iteration. Navigation and educational materials scored perfect, while the scanning feature scored slightly lower, indicating that this is still a subject that could be refined further. Also, the back button and change of language features received feedback indicating that those interactions could be simplified.


Iteration 03

Goal:
The goal of this iteration is to evaluate the refined prototype after addressing all feedback from Iteration 2. The aim is to identify any remaining usability challenges, test the cognitive flow of the app, and ensure the design aligns with user expectations and intuitive interaction. These are the research question that I chose for this iteration
1. Does the refined design facilitate an intuitive and seamless user experience across all features?
2. Are there any cognitive barriers in completing tasks like scanning, sorting, and navigating between pages?
3. How well do users understand and interact with the updated elements, such as the back button, trash bin visuals, and language change feature?
These questions focus on confirming that the design changes resolve prior usability issues and ensure that cognitive processes required to use the app are logical and efficient. Addressing these questions helps refine the app further for practical deployment.
The prototype:
High-Fidelity Prototype
This prototype provides realistic interactions and design elements that simulate the final product, making it suitable for identifying cognitive usability barriers and testing intuitive functionality.
1.Home Screen: Improved accessibility for the language change feature.
2.Trash container Screen: Enhanced visibility and accessibility of the quick guide for waste categories with pictures.
3. Back Button on Trash details Page: Button replaced by the icon.
4.Navigation: Streamlined layout with clearer labeling and icon added on each button.


<img width="468" alt="image" src="https://github.com/user-attachments/assets/e3f76926-7642-462d-a178-2504b6d46968" />

 
Figure: Iteration 3 Layout

Method
I conducted a cognitive walkthrough evaluation method to simulate how first-time users might approach and interact with the application to find out if users can use the app unassisted by an external party to complete tasks.
I selected two friends, who play football with me, to participate in the walkthrough. They had no prior knowledge of the app or its functionalities, making them ideal candidates to test the intuitiveness of the interface.
Tasks Performed:
Task 1: Scan a product using the app.
Task 2: Navigate to the Discover page and understand its purpose.
Task 3: Change the app's language.
Task 4: Use the "Back" button to navigate from sub-pages back to the main interface.

Result:

Task 1: Scan a Product
Observation: Both users characterized the scanning interface as straightforward and were able to finish it in an effective manner. They can scan products without confusion or delay; hence, this functionality is intuitive and easy to use.

Task 2: Discover Page
Observation: One participant immediately grasped the purpose of the Discover page and could navigate it easily. They commented on the layout as being very clean and easy to follow. The other participant also could navigate the page without big problems, proving that the general design was usable, and the categories were placed logically.

Task 3: Change the Language
Observation: Both participants were able to switch the language easily. They liked how clear the language choices were and that it only took a few steps to go through the process. The participants were able to quickly accomplish the task, proving the functionality worked as designed.

Task 4: Back Button
Observation: Both participants were able to use the "Back" button with no problems. It performed as intended, and participants were able to move easily to previous screens. 
Although the participants performed the tasks one by one, I continued my observation of their interaction and behavior with the interface. They managed to complete all four tasks without significant problems; the overall usability, therefore, was smooth. But when they finished, they gave very important insights: one participant stated that adding a loading screen animation in between each transition of the page would further enhance the user experience. They believed this addition would give the interface more dynamism, and that the user would perceive a sense of progression as he or she browsed through its different sections. That such animations were going to build a more motivating atmosphere, creating smoother application flow.

Discussion:
After three iterations, the design solution seems to solve the core problem of waste sorting confusion by providing users with an intuitive and accessible solution. The key functionality of scanning items and receiving sorting instructions is clearly communicated, and user feedback has significantly influenced improvements in usability. From the standpoint of effectiveness, the scanning interface is functional and allows clarity as far as a progress bar to understand if the scanning has been finished. Integrating a quick guide or clearer learning into the education regarding waste categorization and how to work out the application flow would lead to better understanding and result in easier, seamless user flows-essential for the ease of beginners. 
But it can be done even better. For example, the implementation of the loading screen animation might make the use of the application more interactive, as suggested by participants, while refinement of the Discover page would make it visually more appealing; making the switching of languages more seamless would result in better usability.
Consequently, it differs from currently existing applications for waste sorting, as real-time image recognition together with detailed sorting instructions provide an interactive and far more precise experience than text-based sorting guides can provide. This app visually integrates scanning instructions along with a quick guide to categories of waste, which is somehow different from other applications that probably wouldn't have such educative value or guidance at all. Discussion about the Process
The iterative design process really informed some valuable lessons in user-centered design. Each round of feedback from users allowed targeted improvements, showing even the most minute details of design, such as the clarity of instructions or functionality of the back button, may make all the difference in user satisfaction. Diversity within the assessment methodologies-ranging from semi-structured interviews to surveying and cognitive walkthroughs-allows the compilation of a wide range of perspectives that could be used to better understand the strengths and weaknesses of the app. Some of the key takeaways from this process included endless feedback loops. Where low-fidelity prototypes allow for quick and agile changes, switching to high-fidelity prototypes was required when testing realistic interactions and user flows. In this way, the app would sustain the complexity that real usage has, and it provides a better feel for how users will be using the app. 





![image](https://github.com/user-attachments/assets/efe04838-ab54-417c-9cd6-ab43be8dbbf5)



<img width="1127" alt="image" src="https://github.com/user-attachments/assets/2a364263-baa7-4997-85d9-301d5ce4953b" />



<img width="1147" alt="image" src="https://github.com/user-attachments/assets/bb2f7501-c2ed-4b09-813c-b02cbdec5a05" />



<img width="1349" alt="image" src="https://github.com/user-attachments/assets/c9e2056e-8340-411e-88ec-210785a96190" />


 

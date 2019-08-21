# friendFinder

##Getting Started
A link for the deployed site
https://fast-caverns-27870.herokuapp.com/

##Usage
At the home page, click on the button to continue to the survey. Read each statement and decide how much you agree or disagree.  After submitting the survey, the app will parse through the friends api and decide who you are most compatible with.

##Notes
Using JQuery with inline checkboxes proved to be a more difficult task than i had originally thought.
`   for (let i = 1; i <= 10; i++) {
                $(`#question${i} input:checked`).each(function(){
                    answers.push($(this).val());
                });
`

                

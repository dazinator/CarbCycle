## Idea

Android / iOS mobile app to help people on a "carb cycling" diet.


## Features
- Food database for adding food items to your daily food diary.

- Easy Setup
    - Create your profile
        - Age,
        - Height
        - Weight
        - Body type (Ectomorph, Mesomorph etc)
            - Anything else needed to calculate RMR - calculation as per [this](https://globalrph.com/medcalcs/resting-metabolic-rate-rmr/#:~:text=Resting%20Metabolic%20Rate%20(RMR)%20equations%3A&text=(males)%20%3D%209.99%20x%20weight,age%20(years)%20%2D%20161.)
        
    - Create your Goal Types
        - Edit your "Goal Types" - e.g "Low Carb", "Medium Carb" and "High Carb", will be pre-created Goal Types, and set to values based on your body type.
            - Each Goal type has:
                - Name e.g "Low Carb"
                - Macronutrient Ratio e.g:
                    - "Carb: 20%"
                    - "Protein: 40%"
                    - "Fat: 40%"
                - Total calories: e.g 1300 kCal OR No goal for calories (i.e if you just want to eat the correct ratio and don't care about reaching specific calory)
                 
        - Create a Weekly Plan
            - Enter your caloric intake goal for this week, either as an average per day (e.g 1300), or a total for the week.
                - Do you want to lose, maintain weight this week? (Could use this, plus the user's RMR calc to suggest a weekly caloric intake goal)
            - Assign goals to week days:
                - Mon = "High Carb"
                - Tues = "Low Carb"
                - Etc
        - Track Day in Week
            - Meal Plan
                - Add food item (breakfast, lunch, dinner etc)
                - See Current Macro levels vs Goal for Day

 
# [TODO]
- Create solution (.sln) and projects in the `/src` directory.
- Make sure global.json has the right version of the .net sdk.
- For Azure Devops builds:
    - Import pipelines yaml file into Azure Devops pipeline.  
    
    
## Notes

Macronutrients:

1 gram of protein = 4 calories
1 gram of carbohydrate = 4 calories
1 gram of fat = 9 calories
(1 gram of alcohol = 7 calories)

Food database:
       - Can get a good deal of data here: https://world.openfoodfacts.org/data


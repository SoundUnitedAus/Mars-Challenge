# Mars-Challenge

After Virgin Galactic's great success and traces of water being found on planet Mars, goverments of various countries including Australia came together and decided to colonise Mars. After 5 years since this decision they would like to know how the new colony on Mars is growing and also would like to retrieve information of the people living on that planet. Therefore, they are hiring you to build a REST API to provide the desired information.

The goverment will provide you with 2 json files (located at resource folder). One will have information of all the people living on Mars (name, eye colour, age, friends, food items they like to eat and many more...) and another file will have information about all the companies for which the people living on Mars are working for. You will also be responsible for cleaning and organising the data before using it directly from the json files provided. For example, providing a list of favourite foods (in endpoint 3) that each user likes needs to be split into a separate list of vegetables and fruits. 

## New Features
Your API must provide these end points:
- Given a company, the API needs to return all their employees. Provide the appropriate solution if the company does not have any employees.
- Given 2 people, provide their information (Name, Age, Address, phone) and the list of their friends in common which have balance greater than $2000 and are still alive.
- Given 1 person, provide a list of fruits and vegetables they like. This endpoint must respect this interface for the output: {"username": "Sibi", "age": "27", "fruits": ["strawberry", "orange"], "vegetables": ["carrot", "celery"]}

## Delivery
To deliver your system, you need to send the link on GitHub. Your solution must provide tasks to install dependencies, build the system and run. Solutions that do not fit this criteria will not be accepted as a solution. Assume that we have already installed in our environment Python, MySQL, and Redis; any other technologies required must be installed in the install dependencies task.

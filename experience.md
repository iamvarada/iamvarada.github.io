---
layout: default
---
[Projects](./projects.html) | [Experience](./experience.html) | [Resume](https://github.com/iamvarada/CV-Resume/blob/master/Krishna_Varadarajan__Resume.pdf) | [Past Life](http://pravegaracingvit.herokuapp.com/) | [Gimmicks](./gimmicks.html) | [Contact](./contacts.html)

# Experience

```cpp
#include <iostream>
#include <string>

inline const void get_educational_background(const &std::string ed_level) {
	switch (ed_level) {
		case "grad_school":
			std::cout << "School : The Pennsylvania State University\t" << "Duration : Aug. 2016 - May 2019" << std::endl;
			std::cout << "Focus area : Robotics, State Estiamtion, Controls\t" << "Place : University Park, USA" << std::endl;
			break;

		case "undergrad_school":
			std::cout << "School : VIT University\t" << "Duration : Aug. 2016 - May 2019" << std::endl;
			std::cout << "Focus area : Dynamics, Design\t" << "Place : Vellore, India" << std::endl;
			break;

		default:
			std::cout << "Nope, I do not have a doctorate!" << std::endl;
	}
}

inline const void get_experience(const &std::string org_name) {
	switch (org_name) {
		case "rivian_automotive_llc":
			std::cout << "Position : Perception Engineer, Autonomous Driving\t" << "Duration : Sep. 2019 - Present" << std::endl;
			std::cout << "Org Domain : Electric Adventurous Vehicles\t" << "Place : San Jose, USA" << std::endl;
			break;

		case "nio_usa_inc":
			std::cout << "Position : Perception Engineer, Autonomous Driving\t" << "Duration : Nov. 2018 - Sep. 2019" << std::endl;
			std::cout << "Org Domain : Electric Vehicles\t" << "Place : San Jose, USA" << std::endl;
			break;

		case "volvo_group":
			std::cout << "Position : Advanced Technology & Research Co-Op, Connected Vehicles\t" << "Duration : Aug. 2017 - Dec. 2017" << std::endl;
			std::cout << "Org Domain : Connected Trucks\t" << "Place : Hagerstown, USA" << std::endl;
			break;

		case "intelligent_vehicles_and_systems_group_at_penn_state":
			std::cout << "Position : Graduate Research Assistant, Robotics\t" << "Duration : Jan. 2017 - Nov. 2018" << std::endl;
			std::cout << "Org Domain : Robotics, Connected Trucks\t" << "Place : University Park, USA" << std::endl;
			break;

		case "department_of_mechanical_engineering_at_penn_state":
			std::cout << "Position : Graduate Teaching Assistant\t" << "Duration : Aug. 2016 - May 2018" << std::endl;
			std::cout << "Courses Taught: Vehicle Dynamics, Design, Thermodynamics\t" << "Place : University Park, USA" << std::endl;
			break;

		case "indian_institute_of_science":
			std::cout << "Position : Junior Research Fellow, Mechatronics\t" << "Duration : July. 2014 - June 2016" << std::endl;
			std::cout << "Courses Taught: Mechatronics, Assistive Devices, Smart Manufacturing\t" << "Place : Bengaluru, India" << std::endl;
			break;
	}
}

int main(int argc, char* argv[]) {
	const std::string ed_level = std::cin >> "What education level are you looking for? : ";
	const std::string org_name = std::cin >> "Which company's experience are you looking to get detailsfor? : ";

	get_educational_background(ed_level);
	void get_experience(org_name);
}

```
[back](./)
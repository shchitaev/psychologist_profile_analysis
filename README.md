# psychologist_profile_analysis
Проект по анализу профилей психологов, направленное на анализ и понимание профессиональных характеристик и компетенций психологов. 

## Alter

C помощью веб-скрепинга сервиса https://alter.ru/ был собран датасет со следующими признаками:

*	city
*	experience
*	private_experience
*	alter_experience
*	sex
*	age
*	marital_status
*	has_children
*	working_with.family
*	working_with.adults
*	working_with.lgbt
*	working_with.believer
*	working_with.fem
*	working_with.foreigner
*	working_with.elderly
*	education_count
*	competences_count
*	methods_count
*	expertise_count
*	features_of_work_count
*	price

Распределение данных и значения для различных категориальных переменных. Ниже приведены некоторые EDA:

![](https://github.com/shchitaev/psychologist_profile_analysis/blob/main/alter/alter_scatterplot_experience_price.png?raw=true)
![](https://github.com/shchitaev/psychologist_profile_analysis/blob/main/alter/alter_distribution_plots.png?raw=true)
![](https://github.com/shchitaev/psychologist_profile_analysis/blob/main/alter/alter_distribution_of_price_scatterplot.png?raw=true)
![](https://github.com/shchitaev/psychologist_profile_analysis/blob/main/alter/alter_correlation_matrix.png?raw=true)

## Youtalk 

C помощью веб-скрепинга сервиса https://youtalk.ru был собран датасет со следующими признаками и обработан в youtalk_cleaning.ipynb:

*	gender
*	self_appointment
*	messages
*	video
*	audio
*	individual
*	family
*	sync_messages
*	features
*	friendliness
*	lgbtq
*	start_of_practice
*	educations
*	approaches
*	professions
*	work_areas
*	non_working_areas
*	english
*	experience
*	profession
*	age
*	education_counts

Распределение данных и значения для различных категориальных переменных. Ниже приведены некоторые EDA:

![](https://github.com/shchitaev/psychologist_profile_analysis/blob/main/youtalk/youtalk_distribution_plots.png?raw=true)
![](https://github.com/shchitaev/psychologist_profile_analysis/blob/main/youtalk/youtalk_boxplots.png?raw=true)
![](https://github.com/shchitaev/psychologist_profile_analysis/blob/main/youtalk/youtalk_gender.png?raw=true)
![](https://github.com/shchitaev/psychologist_profile_analysis/blob/main/youtalk/youtalk_correlation_matrix.png?raw=true)


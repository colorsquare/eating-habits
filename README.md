# Eating Habits

Eating habits analysis of KAIST students: Focused on the differences before and after COVID-19. Based on HSS001, 2022 Fall, KAIST.

## Abstract

본 연구의 목적은 코로나19가 대학생들의 식사 패턴에 어떤 영향을 주었는지 밝히는 것이다. 이를 위해 식습관 DB의 5가지 항목(식사 유형, 식사 위치, 함께한 사람 수, 이동 거리, 가격)을 이용하여, 코로나19 이전과 이후의 변화를 심층적으로 탐구한다. 구체적인 변화로는 아침 식사의 증가, 기숙사 및 집에서의 식사 증가, 혼밥의 증가, 근거리 식사에서의 이동 거리 감소, 식비 증가로 인한 학생들의 금전적인 부담 증가가 있다. 이 연구는 코로나19 이후 식사 패턴의 변화를 토대로, 교내 학식 및 재정 정책 수립의 기초 자료로 활용될 수 있다.

핵심어: 코로나19, 대학생, 식사 패턴, 식습관

The purpose of this study is to reveal how COVID-19 affected university students' eating patterns. To this end, we explore changes before and after COVID-19 in-depth, using five items of the Eating Habit DB (meal type, meal location, number of people together, travel distance, and price). Specific changes include an increase in the number of breakfasts, an increase in meals at dorms and homes, an increase in eating alone, a decrease in travel distance at close-range meals, and an increase in the financial burden on students due to increased food costs. This study, based on changes in eating patterns after COVID-19, can be used as a foundation for the establishment of school's financial policy and cafeteria management.

Keywords: COVID-19, university students, eating patterns, eating habits

## Data

Data is not disclosed due to privacy. However, below is sample data stored in `database.xlsx`.

| 피험자번호 | 성별 | 연령(만) | 체중유형 | 거주유형 | 전공영역 | 요일 | 식사전스트레스지수 | 식사유형 | 식사위치 | 음식유형 | 가격 | 식사만족도 | 함께한사람 | 이동거리 | 식사시간 | 이동수단 |
| ------- | --- | ------ | ------ | ------ | ------ | --- | ------------- | ------ | ------ | ------ | --- | ------- | ------- | ------ | ------ | ------ |
| A06     | 여성 | 23     | 보통체중  | 자취   | 공과대학 | 금   | 4             | 저녁    | 북측    | 한식    | 5,000 | 약간만족 | 혼밥     | 없음    | 30분이내 | 도보   |
| A06     | 여성 | 23     | 보통체중  | 자취   | 공과대학 | 토   | 2             | 점심    | 어은동   | 양식    | 9,000 | 만족   | 다밥     | 15분이내 | 30분이상 | 도보   |


| Subject Code | Gender | Age | Weight Type | Residential Type | Major | Day of the Week | Stress Index Before Meal | Meal Type | Meal Location | Food Type | Price | Satisfaction | Number of People Together | Distance Traveled | Duration | Transportation |
| ------- | --- | ------ | ------ | ------ | ------ | --- | ------------- | ------ | ------ | ------ | --- | ------- | ------- | ------ | ------ | ------ |
| A06 | Women | 23 | Normal Weight | Living Off Campus | College of Engineering | Friday | 4 | Dinner | North Cafeteria | Korean | 5,000 | A Little Satisfied | Eating Alone | None | Within 30 minutes | Walk |
| A06 | Women | 23 | Normal Weight | Living Off Campus | College of Engineering | Saturday | 4 | Lunch | Eoeun-dong | Western | 9,000 | Satisfied | With Others | Within 15 minutes | Over 30 minutes | Walk |

## Getting Started

Using anaconda,

```shell
$ conda install -c conda-forge pandas
$ conda install -c conda-forge openpyxl
```

family_ceo_transitions.csv -- data dictionary
MGT 510 problem set: Family heir or outside CEO?

12,000 rows, one per CEO transition at a family-controlled firm, 1994-2018. Each firm appears once.
The data are SIMULATED. They were built to resemble the Danish registry data used by Bennedsen, Nielsen,
Perez-Gonzalez and Wolfenzon (Quarterly Journal of Economics, 2007), but they are not those data.

Column                  Meaning
----------------------  ---------------------------------------------------------------------------------
firm_id                 firm identifier
transition_year         year the departing CEO stepped down
industry                one of 8 industries
firm_age                years since the firm was founded, at the transition
assets_musd             total assets in the year before the transition, in $ millions
departing_ceo_age       age of the departing CEO when he or she stepped down
departing_ceo_founder   1 if the departing CEO founded the firm, 0 otherwise
n_children              number of children the departing CEO has (everyone in the data has at least one)
first_child_male        1 if the departing CEO's first-born child is a son, 0 if a daughter
family_ceo              1 if the incoming CEO is a member of the departing CEO's family (child, spouse, sibling
                        or other relative), 0 if the incoming CEO is unrelated (an "outside" CEO)
roa_pre                 operating return on assets, average of the 3 years before the transition, in percent
roa_post                operating return on assets, average of the 3 years after the transition, in percent
roa_change              roa_post minus roa_pre, in percentage points (the outcome)

Notes
- Operating return on assets (ROA) = operating income / total assets x 100.
- A roa_change of -2 means ROA fell by 2 percentage points, for example from 8% to 6%.
- To turn an ROA effect into dollars: (effect in percentage points / 100) x assets.
- There are no missing values.

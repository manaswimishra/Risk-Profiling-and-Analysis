# Insurace Risk Analysis Project

In this project, I have used 2017 data to build a model for finding out probability of customers to ask for a claim in future (2018), along with severity of their claim in USD amount and then create Risk profile based on their probability of asking for a claim.

A glossary for the datasets is provided below:

* pol_number: policy number for the insurance policy
* pol_eff_dt auto insurance policy effective date
* gender gender of driver: F, M
* agecat driver's age category: 1 (youngest), 2, 3, 4, 5, 6
* date_of_birth driver's date of birth
* credit_score driver’s credit score(integer): 1-100, 1=poor, 100=excellent
* area driver's area of residence: A, B, C, D, E, F
* traffic_index traffic index of driver’s area of residence(integer): 100=country average, >100 means worse traffic conditions than average
* veh_age age of vehicle(categorical): 1 (youngest), 2, 3, 4
* veh_body vehicle body, coded as:
                                    BUS
                                    CONVT = convertible
                                    COUPE
                                    HBACK = hatchback
                                    HDTOP = hardtop
                                    MCARA = motorized caravan
                                    MIBUS = minibus
                                    PANVN = panel van
                                    RDSTR = roadster
                                    SEDAN
                                    STNWG = station wagon
                                    TRUCK
                                    UTE = utility
* veh_value vehicle value, in dollar 10,000
* smonths_insured number of months vehicle insurance is bought(integer)
* claim_office office location of claim handling agent: A, B, C, D
* numclaims number of claims(integer): 0 if no claim
* claimcst0 claim amount: 0 if no claim
* annual_premium total charged premium
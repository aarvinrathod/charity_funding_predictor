# charity_finding_predictor

Steps :
    * Load csv using pandas in the dataframe.
    * Condidering column showing success of each applicant as target
    * Cosidering following columns as features
        * Application Type
        * Affilitiation
        * Classification
        * Use Case
        * Organisation
        * Income Amount
        * Asking Amount 
    * Binning Asking amount in following groups 
        * "5k", "5k-10k", "10k-50k", "50k-100k", "100k-500k", "500k-1M", "1M-2M", "2M-5M", "5M-10M", "10M-100M", "100M-1T", "1T+"
    * Creating a list of form names that have less than 50 instances and replacing their name feature with "Other".
    * Creating a list of application type names that have less than 100 instances and replacing their name with "Other".
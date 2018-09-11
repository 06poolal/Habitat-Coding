# Habitat-Coding
    # Coding for turning BBS habitat code into WFBS habitat code


# Proportions CSV's
    # Contains all of the spread sheets which are used to in the code to create the proportions for spring/winter crops,
        # stubble types, crop types, stubble or bare earth etc.
   # Any Stubble.csv
        # Creates the proportion for any WFBS Level 2 stubble type
   # Bean.Lin.csv
        # Creates the proportion of Bean crop to Linseed crop for thier different preceding stubble
   # Bras Stub.csv
        # Creates the proportions of any WFBS Level 2 stubble type which can preced a Brassica
   # Brassica
        # Creates the proportions for any WFBS Level 1 that can preced a Brassica crop
   # C.W Stubble.csv
        # Creates the proportions for clean and weedy stubble types, for WFBS Level 3
   # Lin Stub.csv
        # Creates the proportions for the different types of stubble that can precede a Linseed crop
   # OC Inter.csv
        # Used to create and intermediate in the R code to work out what the proportions were of all of the possible
            # WFBS crops which come from BBS 'Other Crops' (Beans, Linseed, Maize/Sweetcorn, or Other Vegetables/Flowers)
   # OSR.Bean Stub.csv
        # Creates the proportions of any WFBS Level 2 stubble type which can precede an Oil Seed Rape or Bean Crop
   # Pot Stub.csv
        # Creates the proportions of any WFBS Level 2 stubble type which can precede a Potato
   # Sb Stub.csv
        # Creates the proportions of any WFBS Level 2 stubble type which can precede a Sugar Beet crop
   # Sb.Pot.csv
        # Creates the proportions of Sugar Beet and Potatoe in relation to each other to split BBS 'Root Crops' for their
            # different preceding stubble
   # Stubble.Bare Earth.csv
        # Creates the proportions of Stubble to Bare Earth
   # W.Cereals.csv
        # Creates the proportions for the different types of cereal crop which were winter sown
        
        
# Complete_Hab - Copy - Copy (2).R
    # Contains the R code which is used on the Breeding Bird Survey data to translate into Winter Farmland Bird Survey Data


# bbs county to region.csv
    # Used to translate the counties used in the BBS survey into the government NUTS1 regions which the proportions relate to
    
# Validation.R
    # Contains the R code which is used to check whether all of the outputs of the code are correct, against the potential
        # options available for each BBS combination
        
        
# Check.xlsx
    # Contains the data used to check the created data against what the output should be, all of them were created by hand


# Check A.csv
    # Contains the manually created WFBS .xlsxcodes which WFBS Levels 1, 2 and 3a should come out as from the BBS translation


# CheckB2.csv
    # Contains the manually created WFBS codes which WFBS Levels 1, 2, 3a and 3b should come out as from the BBS translation


# Test.csv
    # Contains all the possible combinations of BBS codes, and all the other necessary data needed to be input into the
        # Complete_Hab - Copy.R


# Complete_Hab - Copy.R
    # Used to run the Test.csv code through the R code

# habitat conversion Assumptions (1).xlsx
    # Contains all of the assumptions which were used to create the code and the proportions with the 
        # locations the data came from






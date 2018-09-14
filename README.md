# Habitat-Coding
    # Coding for turning BBS habitat code into WFBS habitat code. Unable to upload the BBS data online, it is
        # subscription only.

# Final_Habitat_Algorithm.R
    # Contains the R code which is used on the Breeding Bird Survey (BBS) data to translate the BBS habitat codes
        # into Winter Farmland Bird Survey (WFBS) habitat codes.


# bbs county to region.csv
    # Used to translate the counties used in the BBS survey into the government NUTS1 regions which the proportion
        # .csv's use


# Proportions CSV's
    # Contains all of the spread sheets which are used to in the code to create the proportions for spring/winter
        # crops, stubble types, crop types, stubble or bare earth etc.
        
   # Any Stubble.csv
        # Creates the proportion for any WFBS Level 2 stubble type
        
   # Bean.Lin.csv
        # Creates the proportion of Bean crop to Linseed crop for thier different preceding stubble
        
   # Bras Stub.csv
        # Creates the proportions of any WFBS Level 2 stubble type which can preced a Brassica
   
   # Brassica
        # Creates the proportions for any WFBS Level 1 that can preced a Brassica crop
        # I need to look at this again and find the proper area of brassicas which are left over winter, a random
            # number has been pulled from thin air (2%)
        # May need to create in intermediary column for this to change it to allow for the different proportions,
            # not sure if the proportions are correct. Must do before publishing
   
   # C.W Stubble.csv
        # Creates the proportions for clean and weedy stubble types, for WFBS Level 3
   
   # Lin Stub.csv
        # Creates the proportions for the different types of stubble that can precede a Linseed crop
   
   # OC Inter.csv
        # Used to create and intermediate in the R code to work out what the proportions were of all of the possible
            # WFBS crops which come from BBS 'Other Crops' (Beans, Linseed, Maize/Sweetcorn, or Other 
            # Vegetables/Flowers)
   
   # OSR.Bean Stub.csv
        # Creates the proportions of any WFBS Level 2 stubble type which can precede an Oil Seed Rape or Bean Crop
   
   # Pot Stub.csv
        # Creates the proportions of any WFBS Level 2 stubble type which can precede a Potato
   
   # Sb Stub.csv
        # Creates the proportions of any WFBS Level 2 stubble type which can precede a Sugar Beet crop
   
   # Sb.Pot.csv
        # Creates the proportions of Sugar Beet and Potatoe in relation to each other to split BBS 'Root Crops' for
            # their different preceding stubble
   
   # Stubble.Bare Earth.csv
        # Creates the proportions of Stubble to Bare Earth
   
   # W.Cereals.csv
        # Creates the proportions for the different types of cereal crop which were winter sown        


# Checking Final Algorithm.R
    # Used to run the Test.csv code through the R code
    # Should be used in conjunction with Validation.R
    
    
# Validation.R
    # Contains the R code which is used to check whether all of the outputs of the code are correct, against the
        # potential options available for each BBS combination, can be used on any output from the algorithm, not
        # just Test.csv
        
        
# Test.csv
    # Contains all the possible combinations of BBS codes, and all the other columns (date, transno, gridref etc.)
        #  necessary to be input into the Checking Final Algorithm.R
        
        
# Check.xlsx
    # Contains the data used to check the created data against what the output should be, all of them were created
        # by hand


# Check A.csv
    # Contains each possible BBS combination for Levels 2 and 4a, and all their manually created potential WFBS codes
        #  for WFBS Levels 1, 2 and 3a as the output should be through the algorithm


# CheckB2.csv
    # Contains each possible BBS combination for Levels 2, 4a and 4b, and all their the manually created potential
        # WFBS codes for WFBS Levels 1, 2, 3a and 3b as the output should be through the algorithm


# habitat conversion Assumptions (1).xlsx
    # Contains all of the assumptions which were used to create the code and the proportions with the 
        # locations the data came from






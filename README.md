# Habitat-Coding
Coding for turning BBS habitat code into WFBS habitat code

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
        # Used to create and intermediate in the R code to work out what the proportions were of all of the possible WFBS
            # crops which come from BBS 'Other Crops' (Beans, Linseed, Maize/Sweetcorn, or Other Vegetables/Flowers)
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

# Check
    # Contains the code which is used to check whether all of the outputs of the code are correct
    
# Hab Complete
    # Contains the R code which is used on the Breeding Bird Survey data to translate into Winter Farmland Birds Data
    

DATA 720 - Programming in python course work
#######################################################
BRANCH DETAILS:
main branch => master , the code will be pushed monthly 
feature branch are created in format yymm-dd-rls
#######################################################

STRUCTURE OF BRANCH:
####################

PROJECT
|----->COURSE UNIT FOLDER(like unit1,unit2,...)
                 |----------->EXERCISE( Asynchronous work for the unit)
                 |----------->DATA(Data used for both Assignment and asynchronous work)
                 |-----------> ASSINGMENT(ASSIGNMENT WORK FOR THE UNIT)

Git commands used to store the git largefilestorageSystem (LFS)
# 1. Install Git LFS (Windows)
git lfs install

# 2. Track CSV files
git lfs track "*.csv"

# 3. Add the LFS tracking file and CSV
git add .gitattributes
git add unit_7/Assignment/Real_Estate_Sales_2001-2020_GL.csv

# 4. Commit changes
git commit -m "Track large CSV with Git LFS"

# 5. Push to GitHub
git push origin 2602-22-rls

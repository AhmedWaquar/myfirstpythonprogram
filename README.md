How it works:
input() collects the user's name and pronouns
pronouns.split('/') splits pronouns like "he/him" into a list ["he", "him"]
[0] gets the first part (he/she/they) and [1] gets the second part (him/her/them)
.capitalize() capitalizes the first letter for starting sentences
The f-string (f"...") inserts the variables directly into the text


# This is a simple code to calculate the remaining age of a person in years, months, weeks and days asuming the person will leave for 90 years.
# current age of person under consideration
current_age = input("what is your current age?:")
print(current_age)
# Age remaining when subtracted from 90 years
age_remaining = int(90) - int(current_age)
print(age_remaining)
# remaining age in years
print(f"Your remaining years is {age_remaining}, years")
# remaining age in months
remaining_age_in_months = int(age_remaining) * int(12)
print(remaining_age_in_months)
# remaining age in weeks
remaining_age_in_weeks = int(age_remaining) * int(52)
print(remaining_age_in_weeks)
# remaining age in days
remaining_age_in_days = int(age_remaining) * int(365)
print(remaining_age_in_days)
print(f"You have {age_remaining} years, {remaining_age_in_months} months, {remaining_age_in_weeks} weeks, and {remaining_age_in_days} days old.")
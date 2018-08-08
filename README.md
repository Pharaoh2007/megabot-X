# megabot-X
now_say = raw_input("what do you want to say?")
print now_say 

from datetime import datetime
now_date_command = datetime.now()
print "do you also want the date"
answer = raw_input ("type yes or no then 'send' it.").lower()
if answer == "Yes" or answer == "yes":
        print '%02d/%02d/%04d' % (now_date_command.month, now_date_command.day, now_date_command.year) 
elif answer == "No" or answer == "no":
        print 'as you want my freind'

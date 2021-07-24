# Protecting-VSI-from-future-attcks-HW

Unit 19 Homework: Protecting VSI from Future Attacks
Scenario
In the previous class, you set up your SOC and monitored attacks from JobeCorp. Now, you will need to design mitigation strategies to protect VSI from future attacks.

You are tasked with using your findings from the Master of SOC activity to answer questions about mitigation strategies.

System Requirements
You will be using the Splunk app located in the Ubuntu VM.

Question 1
Several users were impacted during the attack on March 25th.
Based on the attack signatures, what mitigations would you recommend to protect each user account? Provide global mitigations that the whole company can use and individual mitigations that are specific to each user.

Aplication whitelisting, which will help with identifying attempts to execute malicious code. Ensures that only authorized applications are being executed.


Question 2
VSI has insider information that JobeCorp attempted to target users by sending "Bad Logins" to lock out every user.
What sort of mitigation could you use to protect against this?

Secure wireless networks, this mitigation can block unverified users to try any login attempts on the machine.

Part 2: Apache Webserver Attack:
Question 1
Based on the geographic map, recommend a firewall rule that the networking team should implement.
Provide a "plain english" description of the rule.
For example: "Block all incoming HTTP traffic where the source IP comes from the city of Los Angeles."
Provide a screen shot of the geographic map that justifies why you created this rule.
[
![geo](https://user-images.githubusercontent.com/77302201/126853067-6ed300fe-54eb-475a-9104-3a348bce4d91.png)
](url)
Question 2
VSI has insider information that JobeCorp will launch the same webserver attack but use a different IP each time in order to avoid being stopped by the rule you just created.

What other rules can you create to protect VSI from attacks against your webserver?

Conceive of two more rules in "plain english".
Hint: Look for other fields that indicate the attacker.
Guidelines for your Submission:
In a word document, provide the following:

Answers for all questions.
Screenshots where indicated
Submit your findings in BootCampSpot!

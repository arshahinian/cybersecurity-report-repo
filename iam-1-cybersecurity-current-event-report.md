## (Copyed From Assignment)
# Activity: Cybersecurity Current Event Report
Over the past few lessons we've looked at the contemporary landscape of the Cybersecurity world. We've examined various attack and defense strategies and how those strategies have been employed in various attacks reported in the news. We will now take a moment to report more closely on a couple cyber current events.

# Learning Objectives
Further familiarize ourselves with the contemporary Cybersecurity landscape
Articulate the importance of rigorous application security practices

## Directions
To complete this assignment, we will be researching and reporting on two Cybersecurity current events. Three prospective current events have been listed for your convenience, along with articles containing information about them. We will be writing a 300 word report on each of two Cybersecurity current events. You are free to report on two of the listed events or any other relatively recent (within 10 years) Cybersecurity current event. Complete your reports in an external document that is able to be turned in to your instructor.

# Questions to Keep in Mind
Think of these as guides to your research.

1. What type of attack was this?
2. How was the vulnerability discovered?
3. How were the attackers able to exploit the vulnerability?
4. Were there security measures that could have been taken in order to prevent this attack?

# Events
## 2016 Election
* CNN
## Broadvoice Data Breach
* techradar
## Ukraine Ransomware
* BBC

# Acceptance Criteria
* When the allotted time for this activity is up, learners should have two completed reports with a minimum of 300 words each.
* The reported event must have occurred within the last 10 years.
* Each finished report should have answered the four questions listed above in as much detail as possible.
* Make sure to submit the link to your document.

## (Assignment)

# Event One: Kaseya VSA Ransomware Attack

Kaseya Limited creates and manages information technology and networking infrastructure in America.  They had a vulnerability in software they wrote to manage remote monitoring.  There VSA (Virtual Systems Administrator), the software previously mentioned, had a authentication bypass weakness which allowed REvil hackers to unlawfully access the system and implant a cornucopia of malicious software onto servers that used this software (VSA).
The vulnerability was caught by Researchers of the Dutch Institute for Vulnerability Disclosure.  They detected the weakness and reported it to Kaseya on April 1st, 2021.  Kaseya worked with other company experts to try to patch the issue with no success.
Kaseya Limited did issue a security advisory to all affected users of the software and did shut down any Cloud based services they hosted for SaaS (Software as a Service) service users.
More than, one million systems were compromised by REvil according to them, as they took credit for the attack.  They locked up all the systems and held them hostage by encrypting their systems and not allowing them to access their data without payment of a ransom.  They asked for 70 million dollars to release the systems and unlock them.
This attack was politicized by US President Biden as he asked to meet with Russian president Vladimir Putin to discuss REvil.  REvil is a Russian Randsomware Company, and US President Biden warned that if Putin did not stop this company from working on "US Soil" he would direct his counter cyber hackers to take down REvil’s servers.  Shortly after REvil vanished from the internet and Kaseya got a universal decryptor tool for the REvil-encrypted files from a "Trusted Source".
Political strong arming was the only resolution to this problem.  To prevent this problem in the future the main hackers involved were imprisoned and publicly shamed.  A personally think this does not stop hackers from doing this stuff as it is too much of a reward to get away with it.

* source: https://en.wikipedia.org/wiki/Kaseya_VSA_ransomware_attack

# Event Two: February 2020, Amazon Web Services DDoS Attack

Amazon Web Services was attacked with a DDoS on February 2020, with a peak volume of 2.3 terabits per second.  A denial-of-service attack is a made by a hacker or bad actor when they overwhelm a system by making many requests for service.  They make so many service requests that they slow down or crash the system.  A distributed denial-of-service attack is the same idea, but the perpetrator attacks the target from multiple sources by either procuring the resources to do so themselves, or by taking over (hacking into) many machines to do the dirty work of sending many requests to the target.
The attack was mitigated by Amazon because they were aware it was happening in real time.  Using crazy smart diagnostic and monitoring software, they could see their volume of request going up quickly.  In February the attack spiked the servers up to 2.3 terabits of volume per second. Just to put that in prospective that is more then half of what the UK sees in a day of normal work.
Protecting a system from these attacks is done using many techniques.  I will only mention a few.  Upstream filtering is the first one I will mention, that involves creating a scrubbing area for requests.  This area is usually a proxy server and will look to see if the request is legitimate.  These filters can also act as a traffic cop to limit the number of requests coming from any one IP address.  It can look to see if multiple requests that come in within a few milliseconds “look the same” and seem to be auto generated.  The second technique comes with a Router or a Switch.  Routers and Switches, have rate-limiting capability. They are manually set-up so, be aware that most routers and switches can be easily overwhelmed under a DoS attack and must be sophisticated and configured to help you defend against such attacks.  The final ace in the hole (kind of) are Firewalls.  If the attack is simple, a firewall could have a simple rule added to deny all incoming traffic from the attackers, based on protocols, ports, or the originating IP addresses.  More complex attacks require more sophisticated techniques.

* sources: https://en.wikipedia.org/wiki/Denial-of-service_attack & https://www.bbc.com/news/technology-53093611




                                                                                                                                                                                                                                                

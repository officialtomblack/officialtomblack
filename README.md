### I build privacy & security tools.

Privacy advocate first. Security second. Tools that protect our rights third.

You should be able to use your own devices however you want without being tracked, profiled, or sold. No ad targeting, no quiet data collection, nobody building a file on you from what your phone leaks. Everything below listens, maps, audits, or hides, and none of it attacks anyone.

#### What I've shipped

**[SWIVEL](https://github.com/officialtomblack/SWIVEL)**

Every camera, tracker, and gadget near you is announcing itself into the air. Your phone hears all of it and shows you none of it. SWIVEL puts it on the screen.

It's a passive Wi-Fi and Bluetooth scanner for Android, my fork of [MILLIE](https://github.com/IDEAGREY/MILLIE) by IDEAGREY, and I keep building on it. It sorts what it hears into cameras, trackers, public-safety gear, and network threats. When it hears body-cam, in-car video, or plate-reader vendors like Axon and Flock, it beeps.

- Passive. No deauth, no injection, no jamming, and it never joins a network.
- No accounts, no cloud, no root. Everything stays in the app's private folder.
- It logs everything it hears and exports to CSV, KML, JSON, and WigleCSV.
- One tap on **DURESS** wipes every log and export off the phone.
- It never guesses a maker from a randomized address. It would rather tell you less and be right.

**[DEBRIEF](https://github.com/officialtomblack/DEBRIEF)**

Mine. Feed it your SWIVEL and Kismet logs and it shows what kept showing up wherever you went. Your neighbor's router stays put. A tracker in your bag doesn't. It's offline Python with nothing uploaded and 131 tests, and it's built to cry wolf: a false alarm costs a minute, a missed tag costs a lot more.

#### On the bench

None of this is released yet.

**GHOST-BROWSER**

Runs only in RAM and never touches the hard drive. Close it and it's gone forever. It starts its own server and runs inside it, behind its own VPN kill switch, on a fresh profile that's wiped when you close it. It works with any VPN that gives you a config file. I got it working, and I figured out the anti-fingerprinting.

*Working. Heading to GitHub soon.*

**SANDTABLE**

A network mapper for your own or an authorized network. It maps the network quietly and shows what's exposed. It exploits nothing and does nothing offensive. It writes a tamper-evident log of every action it takes, from the start, for the POC. The gate and the log came first on purpose, and that's what I'm working on now.

*In progress.*

**CYPHER**

Look yourself up, or an authorized client, the way a stranger would. Give it your handles, emails, and sites, or just put in some info, and it shows what the open internet has pieced together. It also uses data breaches, and it researches with 2 loops on each new piece of information about you. It says why it thinks a profile is the right one, with a scoring system. It's made to connect to your state's business database too. It grabs all that info and links to it, even from the big sites that block bots, so you can check yourself, and it makes 3 different reports for you to look up more. If needed, one of the reports tells you how to remove some of that info on yourself. It only runs on you or someone who said yes.

*Working now. The UI and reports are still rough.*

**10-4**

Public-safety radio you host yourself. A cheap SDR dongle, any Linux box, and a link for everyone else. The radio server lives on a VPS, and with 4 antennas covering the county I can hear the unencrypted county, state, and EMT first responders. Clear calls get transcribed as they arrive, and encrypted ones get logged and labeled.

*Still in planning.*

#### Where I stand

Once I saw how much we share without knowing it, and then watched Flock go up right in our faces, it clicked: everything you think you have to buy or pay a monthly subscription for is a lie. Anything can be done or made. You just keep getting up.

I don't like Flock cameras. I don't think a machine should log everyone who drives by, and I really don't think a machine should send out tickets.

Technology is the closest thing we have to a level playing field. They have better tech. The question is whether they use it correctly, and I don't think they do. So I'd rather learn how it works than live under it.

That's why, if THEY feel it's OK to take our DATA, then we can passively take their data and log it. Like they said, "it's for their safety."

#### How I learn

Offensive security, the legal way. I run a Kali lab on a server I own, work through [pwn.college](https://pwn.college), and point my tools only at things I own or labs built to be attacked. Everything else is off limits.

#### The honest part

Am I good at this? Not yet. I keep trying, I keep progressing, and I keep learning, and the climb is the best part. Time is limited, so I spend mine on what I think matters: building privacy tools and pulling apart projects made by people way smarter than me.

**Stack:** Android · Java · Python · Linux · BLE / Wi-Fi RF, and I try to keep data off other people's servers.

**Contact:** [theredwake.sh@protonmail.com](mailto:theredwake.sh@protonmail.com) for questions, bug reports, or collaboration on cyber and AI projects.

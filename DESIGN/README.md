# Mobile App Design

---------------------------------------------------------------------------------------------------------------------------------

# TODO   

Ymy final submission for the deliverable should include the following content:

[ ]  What is ymy app? Include a title, short 'tagline' and a 1-2 paragraph description of what ymy app will do.
[ ]  Describe the main features of ymy app.
[ ] Who are the users of ymy app? Describe user groups, consider constructing user personas, describe how users will use ymy app and why they    might choose it over competitors.
[ ] Illustrate ymy app design with wireframes or mockups (generated with Figma).  These should show both the visual design of ymy app and how    users will interact with it (eg. transitions between screens)  Present ymy design as screenshots interspersed with text.
[ ] Describe which parts of ymy design you will aim to implement for ymy MVP (or what you will leave out)

**1500 - 2000 words**

----------------------------------------------------------------------------------------------------------------------------------

# Name of the app
NiteEcho

# tagline

*Record the silence catch the whispers*

# description and features

Have you ever wondered: Do I sleep talk? Do I snore? Do I sleepwalk? What do I say when I dream? Or perhaps, if you believe in such things, you may even suspect ymy house is haunted and want to uncover the smyce of those strange nighttime sounds.

NiteEcho is an app that lets users listen in on what happens during the quiet hmys of the night. It’s a passive audio recorder that, once activated, continuously monitors ambient sound in the background. When the app detects an anomaly in the usual noise levels—like a voice, a bump, or something unexpected—it begins recording, and automatically stops when the noise returns to normal.

Each recording is saved and available for you to review when you wake up, offering a glimpse into ymy night that you’ve never had before.

All recordings captured by the app are stored in a structured database, allowing users to easily access, manage, and revisit past sleep sessions. Each night the app is active is treated as a separate "session", and sessions are neatly organized in a scrollable list, sorted by date.

Tapping on a session opens a session view, which acts like a folder containing all the audio clips recorded during that specific night. Within this view, users can:
- Play back each recording
- Rename or tag recordings for easier reference (e.g., “Sleep talking”, “Snoring”, “Strange noise”)
- Delete unwanted recordings
- Mark favorites to highlight particularly interesting or recurring sounds

Users can back up their recordings to the cloud to ensure nothing is lost in case local storage becomes unavailable. Additionally, recordings can be shared outside the app via exported audio files, allowing users to send clips to friends, family or even their doctor or sleep specialist.

As someone who experiences nocturnal epilepsy, I'm especially excited about the potential for this app to help users detect nighttime seizures—many of which occur without the person ever being aware. By passively capturing abnormal nighttime sounds, such as sudden movements, vocalizations, or rhythmic noises, the app can provide valuable insight into possible seizure activity. This data could be extremely useful for personal health monitoring and for sharing with healthcare professionals as part of a broader effort to track and better manage seizure patterns.

I will also be adding a feature to cater to people who love mindfulness, lucid dreaming, and inner exploration. I will also have a dream journalling feature which can be linked up to specific audio recordings of the users choice. 


# The target user (user groups)

By using the 5W and 1H we have written up the following information for my targeted user base.

Firstly, who will be using my app? My users can be classed into 5 different groups.

    - Curious sleepers
        who suspect they sleep talk, snore, or sleepwalk and want to hear it for themselves.

    - People with sleep related conditions
        (e.g., sleep apnea, nocturnal epilepsy, night terrors) who want an accessible way to track and reflect on sleep behavior.

    - Health conscious individuals
        aiming to understand their sleep patterns for wellness and improvement.

    - paranormal-curious users
        who suspect strange noises or disturbances during the night.

    - students or researchers 
        interested in sleep studies, behavioral patterns, or audio data collection.

In terms of age my apps users are quite diverse. Ages will range from eight up to sixty five years old. They will also all be comfortable using smartphones

# User personas
By creating fictional user groups I could gain a better grasp of the user base and go back to make adjustments to features I want to include.
-------------------------------------

Walter Melon

Quote: 
    “I swear I heard something move last night. I just need proof.”

BIO : 
    Walter is a 12-year-old student who’s very comfortable using technology. Despite his mum’s warnings, he’s recently been watching horror films like The Conjuring and Annabelle. Now, he often hears sounds at night that leave him feeling anxious. He's convinced his house may be haunted and finds it difficult to sleep alone in his room.

Goals : 
    - Capture nighttime sounds to confirm his suspicions
    - Share spooky recordings with friends
    - Feel a sense of control and reassurance while sleeping

Pain Points :
    - Fear of the unknown while sleeping
    - Lack of evidence to support what he hears at night
    - Doesn’t know how to monitor his environment easily or safely

Design Considerations: 
    - Needs a child-friendly, simple UI
    - Emphasize security and local storage (no sharing without permission)
    - Reassuring tone in design—calming colors, not too clinical or scary
------------------------------------- 

Celeste Noir

Quote :
    “I’ve been seizure-free for years... but lately, something feels off. I need to know what’s happening while I sleep.”

BIO :
    Celeste is a 31-year-old graphic designer living in Melbourne. Diagnosed with nocturnal epilepsy in her early 20s, she’s been managing it successfully with medication and lifestyle changes. Recently, she’s been waking up feeling disoriented and foggy, triggering concern that her seizures may be returning during the night. She’s tech-savvy, health-aware, and proactive about her wellbeing—but she prefers discreet tools that blend seamlessly into her life.

Goals : 
    - Monitor for signs of seizure activity during sleep
    - Capture audio that might indicate involuntary movement or vocalization
    - Have evidence to share with her neurologist
    - Maintain peace of mind and a sense of control over her condition

Pain Points :
    - Uncertainty and anxiety around undetected nocturnal seizures
    - Limited ways to monitor herself without medical-grade equipment
    - Doesn’t want to feel like a “patient” again—needs subtlety, not clinical overload

Design Considerations :

    - Clean, modern, non-clinical UI (think wellness, not hospital)
    - Respectful handling of sensitive health data
    - Easy access to playback, timestamps, and optional cloud backup
    - Ability to flag important recordings for medical reference
-------------------------------------

Zephyr Nebula

Quote :
    “I’m aware in my dreams—but what if I’m saying things out loud too? I want to hear what my subconscious has to say.”

BIO :
    Zephyr is a 24-year-old bloke living in Byron Bay. Deeply immersed in mindfulness, lucid dreaming, and inner exploration, Zephyr considers himself a psychonaut—someone who ventures into altered states of consciousness for personal growth and self-discovery. He keeps a dream journal by his bed and regularly practices techniques like reality checks and dream incubation. Lately, he’s been wondering if his dreams bleed into the real world through sleep talking. To him, NiteEcho isn’t just a tool—it’s a gateway to understanding his subconscious on a deeper level.

Goals :
    - Capture audio of any sleep talking or unconscious vocalisations
    - Correlate recordings with his dream journal for deeper insight
    - Build a personal library of subconscious expressions
    - Share curious or profound audio moments with his close-knit lucid dreaming community
    - Reflect on recurring symbols, sounds, or phrases from altered states

Pain Points:
    - Traditional sleep trackers are too clinical and lack spiritual/emotional focus
    - Manual recording disrupts his sleep rhythm and immersion
    - No existing tools support syncing dream journaling with audio logs
    - Needs an app that respects privacy and doesn’t feel invasive

Design Considerations:
    - Dreamy, immersive UI with calming visuals and soundscapes
    - Ability to tag and annotate recordings (e.g. “Lucid phase”, “False awakening”, “Emotional clarity”)
    - Integration or support for journaling features
    - Strong offline functionality and clear privacy settings
    - A favorite section for his favorite clips?

# How the app will be used

NiteEcho is designed to be simple, intuitive, and seamless—requiring minimal user effort to unlock deep insights into night-time activity. The app’s usage can be broken down into three core stages: setup, sleep, and review.

1. Before sleep. The setup phase.

Users open the app and tap “Start Night Session” to activate NiteEcho. During this phase, they can optionally:

    - Adjust sensitivity (for noisy vs. quiet environments)
    - Set a recording window (e.g. 10PM – 6AM)
    - Enable or disable cloud backup
    - Write a quick pre-sleep journal entry (for lucid dreamers or reflection)

Once activated, the app enters a passive listening mode, running in the background with minimal battery drain. It does not record continuously—only when sound levels deviate from the ambient baseline.

2. During Sleep – Passive Monitoring

While the user sleeps, NiteEcho monitors ambient sound using the phone’s microphone. When it detects an audio anomaly—like a voice, sudden movement, or snore—it automatically:

    - Begins recording
    - Stops when sound returns to baseline
    - Saves the clip to the current night’s session

This passive system ensures only relevant events are recorded, saving both storage and user review time.

3. After Sleep – Review & Reflection

When the user wakes up, they are notified that their Night Session is ready. From here, they can:

    - Tap into the session folder for that night
    - See a list of all captured recordings, sorted chronologically
    - Play, tag, rename, favorite, or delete clips
    - Link clips to dream journal entries (if desired)
    - Share audio clips securely via export

Over time, users build a library of sleep sessions, offering insights into their sleep behavior, health patterns, or subconscious experiences.

# Why my app is better than competitors

Unlike generic sleep trackers or basic voice recorders, NiteEcho is purpose-built for one clear mission: to capture and uncover what happens during the night—without disrupting your sleep. Where other apps either record everything (filling up storage and wasting time) or offer only surface-level analytics, NiteEcho combines smart, sound-triggered recording, organized sleep session management, and personal reflection tools in a seamless experience.

What sets NiteEcho apart :

    🔇 Passive Precision
    NiteEcho doesn't record for hours on end—it intelligently listens for audio anomalies and only records when necessary. This makes it efficient, focused, and respectful of your time and storage.

    🧠 Deeper Insight, Not Just Data
    Most sleep apps give you charts and scores. NiteEcho gives you something real: your own voice, moments, and sounds—helping users build awareness of sleep behaviors, health issues, or subconscious activity.

    🛏️ User-Centric Design
    With carefully considered features like dream journaling, tagging, session folders, and customizable sensitivity, NiteEcho adapts to each user's needs—whether they’re curious sleepers, health-conscious individuals, or lucid dreamers.

    ☁️ Secure & Shareable
    Recordings can be safely backed up to the cloud or shared as exported files, making it easy for users to collaborate with health professionals or connect with like-minded communities.

    🎨 Aesthetic Meets Functionality
    Many apps in this space feel clinical or outdated. NiteEcho prioritizes a soothing, modern interface that feels more like a wellness tool than a surveillance system.

NiteEcho fills a unique gap between sleep health, personal discovery, and effortless tech. It doesn’t just track your sleep—it helps you understand it.

**APP DESIGNS**

### *Wireframes*







### *Mockups* 







    
## Background:
Every major technology we use has equally impressive infrastructure enabling it to exist. This infrastructure tends to get setup as that technological wave is arriving. 
##### Case Studies:
In 1996, Larry Page and Sergey Brin recognised that the world's information was unnecessarily cluttered. They had the foresight to realise that as more information came online, the ability to easily search and traverse it was of utmost importance. So they developed the infrastructure to do so. ([source](https://about.google/intl/ALL_uk/our-story/))

In 2006, Amazon had the foresight to predict that the demand for compute power, storage, memory etc. was only going to grow. They realised if they handled and developed the infrastructure, they'd both supercharge developers (by taking the complexity off of their hands), but also make a killing doing so. ([source](https://digitalcloud.training/a-brief-history-of-aws-and-how-computing-has-changed/)).

##### Today's Landscape:
In terms of AI, we've been on a steady linear acceleration for years now ([source](https://time.com/6300942/ai-progress-charts/)). It's commonly believed that in the future, Action Models will perform many tasks in service of humans. ([source](https://www.gartner.com/en/newsroom/press-releases/2024-03-11-gartner-predicts-one-third-of-interactions-with-genai-services-will-use-action-models-and-autonomous-agents-for-task-completion-by-2028)). This isn't hard to intuit either. 

When GPT-3.5 first came out, one could ask it a complicated request with specific, niche criteria. While it would get the spirit of the request, it would often fail on the minor details. For example, when it first came out, I asked for a workout plan for Mondays, Wednesdays, Fridays and Sundays. It needed to have alternating muscle groups on specific weeks and it had to output all of this in a table format. It would often get the spirit of the request correct, but fail on specifics like having it in a table format or correctly following the muscle group detail.

With GPT-4o, it has rarely failed. Additionally, it has learned the ability to use Python Interpreter as a tool, so if I asked it to calculate calories burned, it could. Extrapolating the trend of models getting smarter and getting better at following instructions, we get the prediction by Gartner above (as well as my personal one on my [GitHub](https://github.com/theCampel/TimeCapsule)). 

I also make a longer-term prediction: We're entering a world where everyone has an AI assistant, AI teacher and each business has an AI representative ([source](https://qz.com/mark-zuckerberg-jensen-huang-meta-nvidia-ai-assistants-1851608544), [source](https://www.gatesnotes.com/AI-agents), [source](https://danielmiessler.com/p/ai-predictable-path-7-components-2024)). This will be made possible because of models' improved ability to follow hyper-specific instructions and use tools. 

##### Predicted Future:
I predict that a potential future workflow would be as follows:

**My Request:** *I want to go see my sister (who lives in Manchester) before the end of the month. It's been an expensive few weeks, so I want to spend maximum £150 round trip. Ideally I'd take the train, but I'm not that fussed. Also she recently texted about a Mexican restaurant that seemed good, so make a reservation there. Also I assume she'll let me sleep on her couch.*

**In The Backend:** The agent would have to do the following:
- Reach out to my sister's AI assistant
	- See the dates and times she's free
	- Check my calendar for dates we're both free
- Reach out to TrainLine
	- Check prices of trains on the dates we're both free
	- Verify that does not break the budget
- Reach out to RyanAir (if TrainLine broke the budget)
	- Check prices and budget again
- Check my texts for the link to the Mexican restaurant she sent
	- Reach out to the restaurant's assistant / booking API to make a reservation. 
- Make a single coherent itinerary

**I Receive:**
- A phone notification with the proposed itinerary, which includes:
	- The RyanAir flights (and the prices of trains - showing they were too expensive)
	- Restaurant booking confirmation
	- The price breakdown of the trip
	- My default payment details to use for the trip
- An option to confirm as is, deny as is, or request changes.
	- For example, I could request that it book the train option it showed me, regardless that it's out of budget.

##### The Idea:
**I want to build the infrastructure that enables the above**. This encompasses: 
- The channel for agents to communicate with each other.
- The platform that allows easy, simple human oversight
- (Potentially) A marketplace for individuals and businesses alike to choose a 



### Things to think about:
- Security
	- Authentication? How do you verify that there's a real human behind it?
		- If you want to communicate behind the platform, would the platform be the authenticator? Avoids millions of bots being able to randomly contact a business - ie. ddos? 

### People to Consider:
There's lots of people 



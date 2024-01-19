# Generative AI Has a Visual Plagiarism Problem

Link: https://spectrum.ieee.org/midjourney-copyright

Notes:
- getting "copyrighted" content from image-generators is pretty easy and simple
- people may use another person's work unknowingly due to "data laundering"
- Midjourney and DALL-E do not do enough to warn users about the potential of this happening
- LLMs can often have the same issues, NYT even went as far as filing a lawsuit against OpenAI
- generative AI can sometimes reproduce its training data, but with minor changes
- it is hard to understand how inputs lead to outputs due to the "black box" nature of generative AI and even their makers don't fully understand what's going on beneath the hood [[emergence]]
- Midjourney and DALL-E were likely trained on copyrighted materials
- Midjourney actually banned someone's account multiple times for investigating this
- Disney, Marvel, Nintendo, etc may decide to follow in the footsteps of NYT
- Napster had to be shut down for less
- larger data may make the systems more prone to reproducing something exactly?
- the problem could be fixed in a number of ways
	- remove copyrighted material from training data - outputs won't be as good?, will be expensive to retrain from scatch
		- figuring out what's copyrighted could also be difficult as copyrighted images may still end up on other parts of the internet without the original creator(s) being acknowledged
	- create patches to prevent people from entering certain prompts or getting certain outputs - people will surely find ways around every patch, and the process of identifying what to patch will surely be difficult/time-consuming ([[ai-dungeon-child-abuse]])
		- existing generative AI guardrails seem to be too strict in some cases and simultaneously too relaxed in other cases ([[toilet-sunbaked-landscape]])
	- filter out sources when creating something - hard to do so due to black box issue
- it's far easier to identify the more brazen examples of copied material like in the case of Marvel, Sonic, etc - but other copyrighted content that got fed into the system has a smaller chance of even being recognised, and if it's recognised it will be harder for the original artists to pursue legal action
- this will be an issue once generative AI dips its toes in music generation


![[a-collection-of-side-by-side-images-show-stills-from-movies-and-games-and-near-identical-images-produced-by-midjourney.webp]]Star Wars-like images created by Midjourney even though Star Wars was never mentioned in the prompts:![[a-collection-of-prompts-and-generative-ai-created-images-which-look-like-star-wars-characters.webp]]Using the word "screecap" in prompts:
![[a-grid-of-six-images-created-by-midjourney-showing-famous-pop-culture-characters.webp]]DALL-E patch:
![[two-screenshots-show-a-dall-e-prompt-that-produced-images-of-c-3po-and-a-prompt-some-time-later-showing-dall-e-not-generating-i.webp]]

#dall-e #midjourney #generative-ai
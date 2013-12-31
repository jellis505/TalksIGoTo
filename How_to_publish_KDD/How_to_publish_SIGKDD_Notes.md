# How to Publish in SIGKDD #

The notes from this are based on the presentation [here](http://www.cs.ucr.edu/~eamonn/Keogh_SIGKDD09_tutorial.pdf).

## 4 Key Questions of Good Research ##
**Think** about these problems before you try to tackle the research that you want to do.

- Is the Problem you are trying to solve important?
- Can you get real data to solve the problem?
- Can you make incremental progress?
	- Tackling a new problem could be tough for a first time researcher, and incremental progress could be a better place to start for younger and less experienced scientists.
- Is there a clear metric for success?


## Finding Problems and Data ##

### Domain Experts ###
- These people often have hard problems, and also can give you the **motivation** for your paper.
- **Latent Need** = What the domain experts want out of the research, they may not even know that it's possible to get what you can offer them either.
	- Calculating the exact quantity over estimating a quantity for them.

### Finding Research Problems
- Suppose *X* works very well...
	- Can you extend *X*? 	
	- Can be argued this type of incremental research is boring and low risk
		- Still can be effective for early career researchers
		- Not all research papers can be ground-breaking...

### Framing Research Problems ###
- Have a clear definition of the problem that you are attacking in the paper.
- The claim should be "falsifiable".
	- Karl Popper = "Falsifability is the demarcation between science and nonscience"

### Finding Data ###
- Synthetic Data is **very** bad.
- Spending the time to make/obtain/clean good datasets will pay off in the long run.
- Use data that people care about.
- **There is no excuse for not using good data**

## Solving the Problem ##

### Complexity of Solutions ###
- Try to avoid complex solutions
	- They do not generalize
	- Harder to cite
	- Harder to explain well
- Simplicity is a strength not a weakness, acknowledge it and claim it as an advantage

### Problem Relaxation
If you cannot solve the problem, make it easier and try to solve the easy version.  This could lead to enlightenment as to how to attack the harder problem, but also a paper in the meantime and more confidence.

### Look to Other Fields for Solutions ###
Adapting a solution from another field can be very enlightening for your research field, and inspire new research directions.

### Eliminate Simple Ideas ###
**Proves** that the problem is worth solving and also proves to yourself that a simple, *unpublishable* solution would not be able to give the same results.

- We must convince the reviewer that this is the simplest way to get results this good.

### Make sure the problem you are solving exists ###
See the sections right before the coffee break in the presentation to discuss this section.

## Writing the Paper ##

### Don't make the reviewer of your paper think ###
> "If you can save the reviewer one minute of their time by spending one hour of your time, you are obligated to do so" - Keogh's (The Author) Maxim

- If you let the reader think they may think wrong!

### 1/3-2/3 Rule ###
- 1/3 of reviewer time is spent on introduction making a decision.
- 2/3 of the reviewer time is spent finding reasons to justify the decision.

### First Page Anchor ###
The reviewer must know after the first page...

- What is the problem?
- Why is it interesting and important
- Why is it hard
- Why hasn't it been solved before?
- What are the key components of the approach and results?
- Summary of Contributions:
	- List the major contributions of the paper 	

### Demonstrating Reproducibility ###
I already took a full semester class on this subject, and therefore already know a ton and have notes on this subject.

### Paper Writing Advice ###
Good advice for paper writing is given here, very similar to the class on academic writing that I took this past year.  No notes are taken on this section, but the slides are well done and useful.

### Top Ten Avoidable Reasons Papers are Rejected ###
Always write your papers thinking about the most cynical reviewers, and do not give them a reason to reject the paper.

1. **This paper is out of the scope of this conference**
	- Reference papers from the conference, reframe the problem...
	- If it really is out of scope, send it somewhere else.
2. **The experiments are not reproducible**
	- Create a webpage with all of the data, paper, and code itself.
3. **This is too similar to your last paper**
	- Spend at least one paragraph describing how this is a reasonable extension of your last work.
4. **You did not acknowledge this weakness**
	- Explicitly acknowledge weaknesses of your algorithm, and discuss why the work is still useful.
5. **You unfairly diminish others work**
	- Send the paper to the people you are criticizing, and see what they say.
6. **There is an easier way to solve the problem**
	- Either include the easy way and show that your way is better, or explain why the simple way would not work in a clear and easy to understand manner.
7. **You do not reference this related work.  This idea is already known**
	- Do a better literature search, or phrase your work as a re-introduction of some result that was lost to the world, and show how it is useful in your new domain.
8. **You have too many parameters/arbitrary choices**
	- For parameters show how the values can be set, or show that the parameters are not important and the end result is not sensitive to the choices.
	- Justify your choices
9. **Not an interesting or important problem**
	- Test on real data
	- Have a domain expert tout it's importance to a particular domain.
10. **The writing is generally careless**
	- Send out an initial draft to mock reviewers!


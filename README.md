# CodeExercise02

Hi there, welcome to Eulith. My name is Lucas, I'm a founder along with Moh and Kristian.

If you're reading this, you're most likely thinking about working with us as a back-end engineer. You no doubt have many alternatives; we deeply appreciate you considering us. 

The below describes a code exercie we give to potential back-end engineers. Our main evaluation criteria (other than assessing the first month of progress when you join) is how you do on the coding exercise. I think it's important to first highlight the "dimensions" we're going to be thinking about:

**1) Your background knowledge going into this exercise.**
Even though this exercise is very "DeFi specific" we've intended it to be for people who do not know Rust and have never worked in DeFi, most likely you have never heard of the 0x project referenced in teh exercise. For people who have a lot of DeFi specific domain knowledge, we'll give a different exercise. We think about how much Rust you knew going into this and evaluate how much you were able to pick up if you chose to use it.

**2) The time you spend on the exersice.**
We'll ask you when you start, how much time you expect to spend on it and evaluate you based on that. You're free to lengthen the initial time allocation if you want (no "points" either way, we'll only look at how long it took in total). The "timer" starts when we send you this repo link. We suggest you start immedately but we don't expect you to finish it in 1 sitting (although you can if you want). We'll look at your github commits and expect you to commit with a certain regularity (i.e. no single commit answers). We view the time you spend as an indication of your interest and work ethic (which we care a lot about). We also view your time spent as a variable of productivity. So there's some "optimization" here where you want to spent enough time to indicate a high work ethic, but not so much time relative to your output that your productivity/hour is low - honestly you shouldn't even worry about this and just do the task for as long as you feel appropriate; the explanation is only to give context.

**3) Your questions and explanations.**
Treat this like you're already working on our team. Naturally, you will have questions and we'll want to understand your approach/implementation. As usual, include any code specific explanations inline. Write your broader explanations that would typically be a conversation in your README. Write your questions in your README (this is part of the submission). Provide context, but try to be _both precise and concise_ about the issue(s), particulalry in your questions.

**4) The work itself.**
Goes without saying, but the most important thing is the code itself. We're going to think about your choice of libraries (if you used any), the benefits and limitations of your design; if this was a PR, what would need to change for us to confidently merge it into our codebase.


Alright! Enough chit-chat. Here it is.

---

Deploy a dummy example of the 0x protocol on a local development chain. 

The dummy example should conform to the 0x's interface (https://github.com/0xProject/protocol/blob/development/contracts/zero-ex/contracts/src/IZeroEx.sol) and return constant values when an ERC20 transform is requested: (https://github.com/0xProject/protocol/blob/development/contracts/zero-ex/contracts/src/features/TransformERC20Feature.sol#L131)

You may use any language, and any local chain you like. We are a Rust shop so bonus points if you use Rust.

Your response should be in the form of a test that:

1. Deploys the relevant contracts to the local chain.
2. Instantiates a contract interface client
3. Calls transformERC20
4. Asserts that the returned constant value is whatever you decided it should be

Please put it in a public Github repo with a README. You may spend as long on this task you like. Get as far as you can and document your progress. If you don't arrive at a working solution, we'll evaluate how you've approached the problem including which tools you've chosen, what simplifying assumptions you've made, etc.

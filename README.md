# CodeExercise02

Hi there, welcome to Eulith. My name is Lucas, I'm a founder along with Moh and Kristian.

If you're reading this, you're most likely thinking about working with us as a back-end engineer. 
You no doubt have many alternatives; we deeply appreciate you considering us. 

The below describes a code exercise we give to potential back-end engineers. 
Our main evaluation criteria (other than assessing the first month of progress when you join) 
is how you do on the coding exercise. 

**When you read this, create a public repo (just with your own github account) and please send us the link to that public repo. You will keep your solution in this public repo.**

I think it's important to first highlight the "dimensions" on which we're going to be evaluating your solution:

**1) The work itself.**
We care about a few things:

- Your code quality: This should go without saying; if you submit a repo that's disorganized, hard to understand,
  contains files that shouldn't be in source control, etc, that's bad. We'll consider the benefits and
  limitations of your design.
- Shipping code that actually works: If you can't complete the whole task, you're better off shipping
  a smaller piece that works instead of just random code here and there that's supposed to show "intentions."
- Dependency decisions: We're going to think about your choice of libraries (if you used any)
  if this was a PR, what would need to change for us to confidently merge it into our codebase.
  We care about how the code is presented, whether it handles reasonable edge cases, whether
  it's robust, whether it's extendable.

**2) The time you spend on the exersice.**
The start time is when you create the public repo mentioned above. You're free to take as long as you want. We suggest 
you start immediately, but we don't expect you to finish it in 1 sitting (although you can if you want). 
We'll look at your Github commits and expect you to commit with a certain regularity (i.e. no single 
commit answers). We view the time you spend as an indication of your interest and work ethic 
(which we care a lot about). We also view your time spent as a variable of productivity. 
So there's some "optimization" here where you want to spend enough time to indicate a high work ethic, 
but not so much time relative to your output that your productivity/hour is low - honestly you 
shouldn't even worry about this and just do the task for as long as you feel appropriate; 
the explanation is only to give context.

**3) Your questions and explanations.**
Treat this like you're already working on our team. Naturally, you will have questions 
and we'll want to understand your approach/implementation. As usual, include any comments in your code
you think will be necessary for us to easily understand your approach. 
Write your broader explanations that would typically be a conversation 
in your README. Write your questions in your README (this is part of the submission). 
Provide context, but try to be _both precise and concise_ about the issue(s), 
particularly in your questions.

This is exercise is associated with this JD, in case the additional context helps 
(it's totally fine if you don't meet all the requirements, this is just for context): 
https://docs.google.com/document/d/13xf1_aaAMdrxoPxtE0k7-mEwwbh5b66nNy-bG_RAXN8/edit?usp=sharing 


Alright! Enough chit-chat. Here it is.

---
NOTE: ALL OF THIS SHOULD BE DEPLOYED ON A LOCAL CHAIN. YOU SHOULD NOT USE REAL-WORLD ASSETS OR ETH FOR ANY OF THIS.

Implement a simple on-chain contract with an accompanying CLI tool. You must use Rust as your programing language, except for the smart contracts. For the smart contracts, we recommend using Ethereum as your blockchain and writing the contracts in Solidity.

Your contract should:
1. Accept ETH or an ERC20 token on your local chain.
2. Define a recipient address.
3. Define some condition upon which the ETH is released to the recipient. For example: "if the recipient sends the secret code, they will receive the ETH"
4. Execute the ETH transfer (on your local chain) when the release condition is met.
5. Do whatever else you think is useful, for example supporting different types of tokens, supporting on-chain events (e.g. oracle calls), etc.

Your CLI tool should be a standalone binary and allow the user to:

1. Deploy your contract to a **local chain**.
2. Set the recipient address.
3. Take an action that satisfies your release condition.
4. Check the balance of the contract or recipient.
5. Reset state to setup the contract for another use.
6. Whatever else you think would be useful.

Production quality code is tested.

Please put it in a public Github repo with a README. 
You may spend as long on this task you like. 
Get as far as you can and document your progress. 
If you don't arrive at a working solution, we'll evaluate how you've 
approached the problem including which tools you've chosen, what simplifying assumptions you've made, etc.

If you finish all of this in like an hour and want to really impress us, put a webserver in front of 
this functionality and allow a user to do the same thing as the CLI through HTTP or Websockets. **This isn't
required.**

---

Just message me if you have any questions, tg: luca590.

When you finish, email the public repo link to: team@eulith.com 
with the subject line: "CodeExercise02 Submission".

Thank you so much for taking the time out to do this assignment. 
We know it's a big time investment and really appreciate your willingness.


## FAQ
...

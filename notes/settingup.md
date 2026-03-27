## super().__init__(model)
- the original mesa.Agent class (the parent) already has its own setup code. 
- It needs to assign a unique_id, set up a random number generator, and link the agent to the model.

##  what is rng
    random number generation
__rng=None (The Default)__ : Every time you run the model, get a different result.  unpredictable.

**rng= any integer**: This is called a Seed. It makes the "randomness" predictable.


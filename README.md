# mt-embedded-llm
LLMs on Embedded Systems (SBCs like Orange Pi 5) through Hardware Acceleration (NPUs). This is my master's thesis.

## Summary
This master's thesis focuses on my open source project [ezrknpu](https://github.com/Pelochus/ezrknpu).
On top of my project, I demonstrate power consumption and performance results, proving a 6 TOPs NPU can run 
DeepSeek R1 (Distill Qwen 1.5B) at around 15 token/s with a power consumption under 8 watts (or under 6 watts, if we ignore the consumption of the AC-DC PSU).

There are two documents, one extended PDF explaining the full thesis, while the other one are some slides summarizing the full work. Both in Spanish.
I recommend taking a look at the ezrknpu repo for English documentation.

## Credits
To the r/RockchipNPU subreddit, which made this open source project possible and even better thanks to their contributions.
Special thanks to the creators of [rknputop](https://github.com/ramonbroox/rknputop) and [GLaDOS on Rock Pi 5](https://www.reddit.com/r/RockchipNPU/comments/1hrywfi/%C2%B5localglados_offline_personality_core/).
I used their projects in this thesis to prove performance usage of NPU and that embedded AI makes sense even with such little power and weak hardware.

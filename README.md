# C++ Learning

This repository is for C++ learning and testing.

At the beginning of the learning curve, being able to test out snipppets of C++ code in Jupyter Notebook is oftentimes so much better than having to create an entire new project in Xcode or something without even knowing the basics. The learning experience is smoother if we can learn C++ the way we (*I*) learned Python. So here's how I got C++ in my Jupyter Notebook. (macOS High Sierra, Version 10.13.6)

- Install `xeus-cling`. Follow the instructions on [xeus-cling GitHub page](https://github.com/QuantStack/xeus-cling). The installation uses `conda`. Read the page for more details of `xeus-cling`.
- `source activate cling` in terminal for activation.
- Use `jupyter kernelspec list` to obtain a list of jupyter environments/kernels (make sure `xeus-cling` is successfully installed).
- *Use `jupyter kernelspec uninstall name_of_kernel` to uninstall the kernel(s) we don't want.
- `cd` back to your normal directory (in my case it would be `cd /Users/Edward/`). When did right, the prompt in terminal reads like this: `~ your_user_name$`, or, in my case, `~ Edward$`.
- Fire up Jupyter Notebook (`~ Edward$ jupyter notebook`).

Of course, this is not to say that we should, or even _could_ stay in Jupyter Notebook for the entirety of our learning curve. I just think that it would be better if beginners start out in Jupyter Notebook so that they're not immediately thrown into projects. My experience is that after some fimiliarization in the notebook, things are easier when I move on to Xcode.

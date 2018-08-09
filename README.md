# C++ Learning

This repository is for C++ learning and testing.

At the beginning of the learning curve, being able to test out snipppets of C++ code in Jupyter Notebook is so much better than having to create an entire new project without knowing anything. The learning experience is smoother if we can learn C++ the way we learn Python. So here's how I got C++ in my Jupyter Notebook. (macOS High Sierra, Version 10.13.6)

- Install `xeus-cling`. Follow the instructions on [xeus-cling GitHub page](https://github.com/QuantStack/xeus-cling). The installation uses `conda`.
- `source activate cling` in terminal for activation.
- Use `jupyter kernelspec list` to obtain a list of jupyter environments/kernels (make sure `xeus-cling` is successfully installed).
- *Use `jupyter kernelspec uninstall name_of_kernel` to uninstall the kernel(s) we don't want.
- `cd` back to your normal directory (in my case it would be `cd /Users/Edward/`). When did right, the prompt in terminal reads like this: `~ your_user_name$`, or, in my case, `~ Edward$`.
- Fire up Jupyter Notebook (`jupyter notebook`).

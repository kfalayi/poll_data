# polls-eda

Lesson plan for conducting exploratory data analysis.

1. `polls-eda.ipynb`
2. `scratchpad.ipynb`

**As you go through the lessons, pay attention to the following emojis:**

👉- something you need to do (usually write code in the cell below, or maybe a short answer or a longer reflection in a markdown cell)

📚- something you should read (other links are there if you want to follow them, but not required reading)

🤖- Totally optional stuff for students who are already familiar with the concepts we're learning in this lesson.


## Setup

1. Make sure you have the following packages:

	```shell
	pip3 install jupyter plotnine pandas
	```

2. Make sure you're in the right folder on your terminal (I like to store things in my `~/Development` folder, but you can keep them elsewhere if you prefer).

	```shell
	# enter the folder where you plan to clone this repo
	cd ~/Development
	
	# make sure you got there (read the output!)
	pwd
	```

3. Next, clone this repository by clicking the green button in the upper right corner, selecting `SSH` and copying the string that looks like `git@github.com:code4policy/<REPO-NAME>.git` (`<REPO-NAME>` will be the name of your repository). Then, in the terminal run the following:

	```shell
	git clone git@github.com:code4journalism/<REPO-NAME>.git
	```

	Note that by default, git will clone the repository into a folder with name `<REPO-NAME>`. After the repo is cloned, open that directory (use `cd` to get into the folder you just cloned).

4. Run the jupyter notebook and open up `exploratory-data-analysis.ipynb`

	```shell
	jupyter notebook
	```

	Make sure you're using a python3 kernel in Jupyter!


## How to Submit

Whenever you stop for the day, just save each notebook and commit it to GitHub so that the most recent version is up. If you plan to ask for help, it can also be useful for the teaching team to see where you're stuck by just looking at your repo! We won't grade it until you submit via Courseworks. 

Remember, we're all learning so pushing messy code is okay! 

When you're ready to submit, you may want to do a bit of cleanup.
Make sure that all the cells you want us to grade and provide feedback on have been run and are visible before you push. Ideally the notebook can be re-run from top to bottom.

You may have modified the example charts from the original, and that's totally okay too! I like to see that you're taking the time to explore, understand, and tinker.

When you're ready, push the completed assignment to GitHub and put a URL in courseworks. We'll consider the assignment ready to grade once it has been submitted there!

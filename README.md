# Building a Decision Tree From Scratch!
![This is an image](https://i.imgur.com/kVLpMYM.png)

(Depicted: A visual representation of a single decision tree in my trained random forest model!)


<br/>

> ## 🤔 Purpose
This is my second attempt at building an ML model from scratch in hopes of gaining a more **fundamental understanding of the mathematical and statistical concepts behind ML algorithms**. After doing some digging, I found random forests to be one of the simplest and most effective classifier algorithms. Since random forests are derived from (as the name might suggest) a forest of decision trees, I embarked on a mission to **use Python to build a decision tree algorithm entirely from scratch WITHOUT referencing any code.** Afterwards, I wanted to actually train and implement a random forest model using a pre-existing ML model.

<br/>

> ## ⚙️ Process
1.  I watched videos and read articles in order to get a high-level understanding of the random forest algorithm WITHOUT looking at any actual code. Sources I heavily referenced include [this video](https://www.youtube.com/watch?v=jVh5NA9ERDA) and [this video](https://www.youtube.com/watch?v=eM4uJ6XGnSM).
3. After much struggle deciphering mathetmatical equations, I was able to create accurate entropy and information gain calculators.
4. I built out the decision tree class with very ugly and redundant code, but hey! At least I was understanding it more. 
5. Referenced more articles and videos (WIHTOUT CODE) to learn how to fit the decision tree model to a training set and then apply the fitted model to unseen data. After some trial-and-error, my model proved to be successful!
6. Using scikit-learn's random forest classifier algorithm, **I trained and evaluated my very first random forest model.** Helpful videos I referenced to train the model include [this one](https://www.youtube.com/watch?v=FiHfrv2q-I4) and [this one](https://www.youtube.com/watch?v=eM4uJ6XGnSM)
7. Finally, to top it all off, I dabbled with some **data visualization techniques** in order to get some pretty neat graphical representations of the decision tress within my random forest, just like the one included at the very top of this README file!

<br/>

> ## 👍 Victories and 👎 Challenges
1. 👍 Created a working decision tree algorithm that can classify a datapoint from a dataset consisting of two features, two target classes, and one target. [Code linked here!](decision_tree_algorithm.ipynb)
2. 👍 Successfully **trained and deployed my very first random forest algorithm** using scikit-learn's model!
3. 👍 Learned how to vizualize decision tree data using mathplotlib and scikit-learn libraries.
4. 👎 Messy decision tree code with lots of redundancies and inefficient systems.
5. 👎 I tried to derive a random forest algorithm from scratch using my decision tree algorithm, but didn't get very far. I found it to be an extremely conceptually challenging task to do so without referring to ANY code. So, I decided to code only decision trees from scratch and instead use scitkit-learn's model for a random forest algorithm. Maybe in the future I'll take on this random-forest-from-scratch challenge again...


<br/>

> ## 🔭 Conclusion
I'd very much like to create a random forest algorithm from the ground up, but maybe not entirely on my own... I think it's time that I enlisted the help of tutorials from now on. As it turns out, I may actually end up learning MORE with tutorials as opposed to before, where I would just create my own messy algorithms with a very brute-force, point-A-to-point-B mindset, rather than a thought-out and methodical one. Bottom line is, I'll do my best to ensure a balance between learning from other people's code and doing it myself so that I'm able to make much cleaner code without copying off someobdy else. That way, I'll be able to translate and implement the code in ways that I can easily understand and manipulate. That being said, I'm very satisfied with the outcomes of this project — I was able to grasp new ML concepts, challenge my problem-solving skills, and learn new data analysis techniques! I'm planning on tackling genetic algorithms and neural networks from scratch next... **but for now: a nap.**

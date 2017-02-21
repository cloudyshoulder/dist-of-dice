# dist-of-dice
Distribution of fair dice

Initialization code

	mean = Mean@Range@6;
	sd = Sqrt[Sum[(i - mean)^2 /6, {i, 6}]];

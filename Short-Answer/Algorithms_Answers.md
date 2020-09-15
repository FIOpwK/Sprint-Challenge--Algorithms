#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)


b)


c)

## Exercise II

Suppose that you have an n-story building and plenty of eggs.
Suppose also that an egg gets broken if it is thrown off floor f or higher, and doesn't get broken if dropped off a floor less than floor f.

Devise a strategy to determine the value of f such that the number of dropped + broken eggs is minimized.

Write out your proposed algorithm in plain English or pseudocode AND give the runtime complexity of your solution.

n = num_of_floors
f = floor_of_n

number_of_eggs = random
dropped_eggs = 0
broken_eggs = 0

#Understand: the numer of dropped_eggs from f floor is random, the number of broken_eggs depends of f
## if f is 0, then no dropped_eggs are broken_eggs
## however, if f is greater than 1, some eggs might break while others are not broken

#Plan: the idea is to test how many eggs can be dropped from f floor without dropped_eggs == broken_eggs
# so, if floor is 5, and we drop 2 eggs, we need to know if all, none or at least one egg is broken





- input?
 = f, n, number_of_eggs

def minimize(f, n, number_of_eggs):

    #we have a base case where
    if n == 0:
        #all eggs dropped and no eggs broken, ideally
        return broken_eggs + broken_eggs
    else:
        while
    pass



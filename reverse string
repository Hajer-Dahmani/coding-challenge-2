# coding-challenge-2
import copy

def reverseString(L):
    if isinstance(L,list) == True:
        count = 0
        for element in L:
            if (len(element) == 1) and (element.isalpha()) :
                count += 1
        if count == len(L):
            for i in range(len(L)//2):
                copy1 = copy.copy(L[i])
                copy2 = copy.copy(L[len(L)-1-i])
                L[i] = copy2
                L[len(L)-1-i] = copy1
        return L

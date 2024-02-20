# Print-the-runner-up-score.
Print the runner-up score in hacker rank
Given the participants' score sheet for your University Sports Day, you are required to find the runner-up score. You are given  scores. Store them in a list and find the score of the runner-up.

Input Format

The first line contains . The second line contains an array  Ap[] of n integers each separated by a space.
Constraints

2<=n<=10



solutions:
if __name__ == '__main__':
    n = int(input())
    arr = map(int, input().split())
    newarr=set(arr)
    newarr.remove(max(newarr))
    print(max(newarr))

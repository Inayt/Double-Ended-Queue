# Double-Ended-Queue
import collections
#create a deque
DoubleEnded = collections.deque(["Jay","Rishi","Surya"])
print (DoubleEnded)

#Append to the right
print("Adding to the right:")
DoubleEnded.append("Faraaz")
print(DoubleEnded)

#Append on left side
print("Adding to left:")
DoubleEnded.append("Mosin")
print(DoubleEnded)

#Remove from right
print("Remove from right:")
DoubleEnded.pop()
print(DoubleEnded)

#Remove from left
print("Remove from left:")
DoubleEnded.popleft()
print(DoubleEnded)

#Reverse
print("Reversing deque:")
DoubleEnded.reverse()
print(DoubleEnded)

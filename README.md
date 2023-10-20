# Compare-within-margin

## Function that accepts 3 parameter: a,b and an optional margin. The function should return wheter a is lower than, close to or higher than b.

def close_compare(a, b, margin=0):
    if abs(a - b) <= margin: return 0
    elif a < b: return -1
    else: return 1

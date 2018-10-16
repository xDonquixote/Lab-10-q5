def get_sum(t):
    if(t == None):
        return 0
    else:
        return t.data + get_sum(t.left) + get_sum(t.right)

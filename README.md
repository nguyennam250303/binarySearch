# binarySearch
    def binarySearch(a,k):
    
        l = 0
    
        r = len(a) - 1
    
        while l <= r:
    
            mid = (l + r) // 2
    
            if k == a[mid]:
    
                return mid
    
            elif k > a[mid]:
    
                l = mid + 1
    
            else:
    
                r = mid - 1
                
        return -1

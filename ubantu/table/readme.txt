usage : 


from table import TableRepositories 
TableRepo = TableRepositories(path_to_image) 

#print(TableRepo.response)
#cv2.imwrite ('slate.png', TableRepo.slate)
#cv2.imwrite ('mask.png', TableRepo.mask)
#cv2.imwrite ('filtered.png', TableRepo.filtered)
img= cv2.imread('TableRepo.slate/slate.png',0)
cv2.imshow("TH2",img)
cv2.waitKey()
cv2.destroyAllWindows()

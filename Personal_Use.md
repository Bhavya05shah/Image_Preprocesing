Understanding different code snippets and data types being used in here
thresh = cv2.threshold(blur, 0, 255, cv2.THRESH_BINARY_INV + cv2.THRESH_OTSU)[1]
For this fucntion---> cv2.THRESH_OTSU
It automatically calculates the optimal threshold value.

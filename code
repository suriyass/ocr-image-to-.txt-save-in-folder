try:
    from PIL import Image
except ImportError:
    import Image
import pytesseract
import os.path
save_path = '<path_to_save_file>'
file_name = raw_input("What is the name of the file: ")
fullName = os.path.join(save_path, file_name+".doc")         
file1 = open(fullName, "w")
file1.write(pytesseract.image_to_string("test.png").encode('utf-8').strip())
file1.close()

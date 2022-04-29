# yyyyjk#created by Danila

#upgrede by Ozodbek Haitov

try:
    class Telegram:
        def __init__(self ,mesage,nickname):
            self.mesage = mesage 
            if u == "!":                                       print("{0}".format("[" + nickname + "]" + " " + mesage + "!"))
            elif u == "?":                              print("{0}".format("[" + nickname + "]" + " " + mesage + "?"))
            elif u == ".":                print("{0}".format("[" + nickname + "]" + " " + mesage + "."))
            elif u == "None":
                print("{0}".format("[" + nickname + "]" + " " + mesage))
            elif u == " ":
                raise TypeError

    i = input()

    u = input()

    nickname = input()
    
    main(i,nickname)

except:
    print("Error!|Ошибка!")




















def print_happy_birthday(name):
    print(f"""
    H A P P Y   B I R T H D A Y, {name.upper()}!
    ==========================================
    
    H   H   A   PPPP  PPPP  Y   Y
    H   H  A A  P   P P   P  Y Y 
    HHHHH AAAAA PPPP  PPPP    Y  
    H   H A   A P     P       Y  
    H   H A   A P     P       Y  
    
            __
           /  \\
          |    |
          |    |
           \\__/
            ||
            ||
            ||
            ||
            ||
          /____\\
    ==========================================
    """)

if __name__ == "__main__":
    name = input("Enter the birthday person's name: ")
    print_happy_birthday(name)

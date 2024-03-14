# exit2
import sys

def main():
    print("This is a simple program.")
    choice = input("Do you want to exit? (yes/no): ")
    if choice.lower() == "yes":
        print("Exiting the program...")
        sys.exit()
    else:
        print("Continuing execution.")

if __name__ == "__main__":
    main()

# my-ninteenth-repo
my test repo
import rando
import string

chars = string.ascii_letters + string.digits + "!@#$%^&*"
password = "".join(random.choice(chars) for _ in range(12))
print("Generated password:", password)

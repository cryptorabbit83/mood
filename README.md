# mood
# motivation_boost.py

def boost_mood():
    messages = [
        "You're doing better than you think.",
        "It's okay to pause. Just don't quit.",
        "Small steps still move you forward.",
        "You are not alone. You're just tired.",
        "Rest. Breathe. You've got this."
    ]

    from random import choice
    print("\n💬 " + choice(messages) + "\n")

if __name__ == "__main__":
    boost_mood()
boost_mood new

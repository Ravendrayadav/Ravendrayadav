from string import ascii_lowercase
print(' --: WELCOME TO QUIZE GAME !! :--')

print("NOTE : Please enter there charecter of your answer")
playing = input("Do you want to play?")
if playing=='yes':
   QUESTIONS = {
    "what is your name ?": [
        "ravendra",
        "raghunath",
        "manohar",
        "ankit",
    ],
    "were do you live ?": [
        "kudri",
        "sarra",
        "katariya",
        "other",
    ],
    " what do you do in present?":[
    "study","job ","work","other"],
}

   num_correct = 0
   for num, (question, alternatives) in     enumerate(QUESTIONS.items(), start=1):
    print(f"\nQuestion {num}:")
    print(f"{question}?")https://github.com/Ravendrayadav
    correct_answer = alternatives[0]
    labeled_alternatives = dict(zip(ascii_lowercase, sorted(alternatives)))
    for label, alternative in labeled_alternatives.items():
        print(f"  {label}) {alternative}")

    while (answer_label := input("\nChoice? ")) not in labeled_alternatives:
        print(f"Please answer one of {', '.join(labeled_alternatives)}")

    answer = labeled_alternatives[answer_label]
    if answer == correct_answer:
        num_correct += 1
        print("⭐ Correct! ⭐")
    else:
        print(f" choosing a wrong  answer :-    {answer!r}, Right is answer:-{correct_answer!r}")
    print(f"\nYou got {num_correct} correct out of {num} question")
else:
    print("thank you are out of game")
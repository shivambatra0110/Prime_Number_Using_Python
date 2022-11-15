# Prime_Number_Using_Python
To Check Whether the Number is Prime or Not (Using Python)
{
   "cell_type": "code",
   "execution_count": 1,
   "id": "ef01a3bf",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Enter a Number: 5\n",
      "5 is a Prime Number\n"
     ]
    }
   ],
   "source": [
    "# To take input from user \n",
    "Number = int(input(\"Enter a Number: \"))\n",
    "# Prime Number are always greater than 1\n",
    "if Number > 1:\n",
    "#check for Factors using if else  \n",
    "    for i in range(2,Number):\n",
    "        if (Number%i) == 0:\n",
    "            print(Number,\"is not a Prime Number\")\n",
    "            break\n",
    "    else:\n",
    "        print(Number,\"is a Prime Number\")\n",
    "# If input number is less than or equal to 1, it is not a prime Number\n",
    "else:\n",
    "    print(Number,\"is not a Prime Number\")"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.9.12"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}

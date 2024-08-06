# Song-Lyrics-Generation-Model
A machine learning model for generating song lyrics using advanced neural network techniques. This model leverages Bi-directional LSTM to create coherent and creative lyrics in various styles.

## Table of Contents
- [General Steps](#general steps)
- [Implementation Details](#implementation details)
- [Example](#example)
- [Applications](#applications)
- [Contact](#contact)

## General Steps
1. Predict the next word in the sequence
2. Feed old input plus a new output word as the next input
3. Make the output a one-hot encoded label over entire corpus of desired text outputs
4. Utilize categorical cross entropy loss function as the output will be multi-class

## Implementation Details

**Model Architecture**: Bi-LSTM, Embedding

**Epochs**: 200

**Accuracy**: 88.65%

The learning curve is shown below: 

![image](https://github.com/user-attachments/assets/bc4bc9d6-ce88-4dcf-ad3a-7e8466434e43)

## Example
**Input** = "im feeling chills"

**Total Words Predicted** = 100

**Output** = "im feeling chills me girl she to fight so fine fine fine see do do what could i do mine mine mine mine sender music hardly need cassandra bang a boomaboomerang is love in return to do what could here again cause i did sender am song chiquitita do of wrong truth do i do mine mine mine again i sender music hardly need boomaboomerang you had think crazy sun song song question new bone bone body sucker music music bang as new song chiquitita you had didnt notion do mine wrong fingers sleep shoulder did start start start morning dont wrong wrong"

## Applications
- Songwriting: Assists songwriters and musicians in generating creative and novel lyrics, providing inspiration or even complete lyrics for new songs.
- Lyric Variations: Creates multiple variations of lyrics for the same melody or theme, offering different perspectives or styles.

## Contact
LinkedIn: [Zainab Siddiqui](https://www.linkedin.com/in/siddiquizainab/)

# Book_writer_LSTM
 ### 
<strong> It uses LSTM to learn writing a book character by character.</strong>

### Dateset
Dataset is provided with the repository in the file <strong>anna.txt</strong> . It should be kept in the same directory as the code. 

### Model description
Code for the LSTM is provided in the notebook CharRNN.ipynb. The model is created in the class named CharRNN.
1. Model Structure
      - Hidden layers : 256
      - Number of LSTM layers : 2
      - Input size : 83
      - Output size : 83
      
2. Loss : Cross Entropy Loss

3. Optimizer : Adam optimizer

### Usage
To use the code, execute all the cells in CharRNN.ipynb and send the required arguments in sample function.

      sample(model, 1000, prime='Anna', top_k=5)

      
### How to Contribute
Find any typos? Have another resource you think should be included? Contributions are welcome!

* Fork this repository.

* Clone the repository to your desktop to make changes.

      $ git clone {YOUR_REPOSITORY_CLONE_URL}

* Issue a pull request by clicking on the green pull request icon.

Instead of cloning the repository to your desktop, you can also go to README.md in your fork on GitHub.com, hit the Edit button (the button with the pencil) to edit the file in your browser, then hit the Propose file change button, and finally make a pull request.

### License
This repository has been licensed under Apache 2.0.

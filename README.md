# Advanced-NLP-Project
Distributed Representation of Words and Phrases and their Compositionality.

In the paper “Distributed Representations of Words and Phrases and Their Compositionality,” the 
researchers offer an improved skip-gram model for learning word vectors, which greatly advances the 
quality and speed of word representations. Key milestones consist of subsampling for frequent words 
to boost training as well as representation of infrequent words; it also introduces negative sampling as 
an alternative to hierarchical softmax. These techniques not only make training more efficient but also 
help the model capture better syntactic and semantic relations between words. Besides, another issue 
that is addressed in the paper is representing phrases and idiomatic expressions used in detecting such 
phrases and forming vector representations.

Objective
The outcome of this research paper is to increase the capabilities of the Skip-gram model to further enhance 
the word vector quality, accelerate the training process and effectively handle the representation of 
phrases that cannot be simply created from their individual word components.
To achieve these goals, the researchers suggested a number of significant changes and enhancements 
to the existing model of Skip-gram. During the training phase, they first incorporate frequent word 
subsampling. By decreasing the number of regular words that must be processed frequently, this method 
greatly expedites the training process while simultaneously enhancing the quality of the representations 
for uncommon words. The model can catch more significant links between words and improve the 
overall accuracy of the word vectors by concentrating on less common terms.
In addition to the hierarchical SoftMax strategy, the study proposes a negative sampling method for 
training the skip-gram model. By using fewer negative samples than positive samples, negative 
sampling reduces training times and increases representation accuracy, especially for terms that appear 
frequently. This solution is also more computationally efficient because it does not involve computing 
the entire SoftMax function. The paper, for example, shows that the hierarchical softmax approach with 
Huffman codes required 41 minutes to achieve a total accuracy of 47% on the analogical reasoning task, 
whereas negative sampling with five negative samples required 38 minutes of training and a total 
accuracy of 59%.
Another important contribution of this research paper is the development of a process for representing 
phrases as unique tokens rather than just combinations of their constituent words. This process mainly 
addresses the drawbacks of initial word vector representation, which have difficulty in understanding 
multi-word and idiomatic sentences. For example, the meanings of "New York" and "Times" cannot be 
easily combined to represent "New York Times," a widely known newspaper. During the training 
process, the model can create more accurate and intelligible vector representations for phrases like 
"New York Times" by treating them as separate units, hence increasing the model's ability to handle 
more complex language structures.
In Conclusion, the main objective of this paper was to improve the Skip-gram model's word vector 
quality, speed up training, and enable effective phrase representation. Natural language processing
(NLP) will benefit greatly from these enhancements, which will finally increase the model's 
effectiveness and capacity to capture a greater range of linguistic complexities

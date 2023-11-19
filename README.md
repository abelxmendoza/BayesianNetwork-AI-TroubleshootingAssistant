# Bayesian Network Troubleshooting Assistant

## Project Overview

This project, completed as part of the **Artificial Intelligence** class (CPSC 481-05) at California State University, Fullerton, under the guidance of Professor  **Kenytt Avery**, focuses on the implementation and application of Bayesian Networks to model and analyze network-related uncertainties. The project includes the development of a Bayesian Network to represent the dependencies among different components in a network system, sampling algorithms for inference, approximate inference methods, and a troubleshooting assistant using Bayesian reasoning.

## Authors

* Abel Mendoza
* Divyansh Mohan Rao
* Hiep Do
* Jarred Ethen Siriban
* Samad Ahmad
* Santiago Zavala

## Project Structure

1. **Implementation of Bayesian Network:**
   * The project begins with the creation of a Bayesian Network to model a network system. The network includes variables such as Cable, DHCP, DNS, DataCenter, NetworkConfig, DnsConfig, WebServer, and WebPage. Conditional Probability Tables (CPTs) are provided for each variable to capture the dependencies.
2. **Sampling Algorithms:**
   * Sampling algorithms, such as enumeration sampling and prior sampling, are employed to estimate probabilities and make inferences about the network's behavior.
3. **Approximate Inference:**
   * The project addresses queries related to the network's functionality using rejection sampling for approximate inference. Questions include the likelihood of an employee accessing the web page, the status of the web server, and more.
4. **Comparison with Joint Distribution:**
   * A comparison is made between the results obtained through approximate inference and the joint distribution using the `enumeration_ask` method.
5. **Troubleshooting Assistant:**
   * A troubleshooting assistant is developed to assist users in diagnosing network issues. The assistant utilizes the Bayesian Network to identify the most probable cause of network failure based on user input regarding the status of different components.

## How to Run

1. **Requirements:**
   * Jupyter Notebooks
   * Python
2. **Cloning the Repository:**

```bash
git clone <repository-url>
cd <repository-directory>
```

3. Running the Notebook

   * Open the `Uncertainty.ipynb` notebook in Jupyter and run the cells sequentially.
4. **Troubleshooting Assistant:**

   * The troubleshooting assistant section in the notebook provides an interactive interface to diagnose network issues. Follow the prompts to input the observed status of network components.

## Results and Conclusions

The project successfully implements a Bayesian Network for network uncertainty modeling, demonstrates various sampling algorithms, performs approximate inference for specific queries, and creates a troubleshooting assistant based on Bayesian reasoning. The results of queries and troubleshooting scenarios provide insights into the network's behavior under different conditions.

## About Bayesian Networks in AI

Bayesian Networks are graphical models that represent probabilistic relationships among a set of variables. They are widely used in artificial intelligence for reasoning under uncertainty. By capturing dependencies between variables, Bayesian Networks enable efficient inference and decision-making, making them a valuable tool in AI applications, including diagnostics, decision support, and risk analysis. This project showcases the practical application of Bayesian Networks in modeling and troubleshooting network-related uncertainties.


## Acknowledgments

We would like to express our gratitude to Professor **Kenytt Avery** for his guidance and support throughout the Artificial Intelligence course at California State University, Fullerton. His insights and expertise significantly contributed to the successful completion of this project.

## License

This project is licensed under the MIT License - see the [LICENSE](https://chat.openai.com/c/LICENSE) file for details.

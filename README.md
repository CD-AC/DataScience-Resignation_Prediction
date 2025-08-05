<!DOCTYPE html>
<html lang="es">

<body>
    <h1>EMPLOYEE RESIGNATION PREDICTION</h1>
    <p><img src="https://raw.githubusercontent.com/CD-AC/DataScience-Prediction_Models_HR/main/DataFlow.png" alt="Banner Image"></p>
    <h2>Introduction</h2>
    <p>In this article, a predictive analysis is presented regarding the potential resignation of employees. The main objective is to develop three prediction models using machine learning techniques to identify employees who may be considering leaving the company in the near future. This analysis aims to assist companies in taking proactive measures to retain their key talent and improve job satisfaction.</p>
    <h2>Research</h2>
    <h3>Cost of Hiring an Employee in 2024</h3>
    <p>This article analyzes the average cost per hire in the year 2024 and the factors influencing this cost.</p>
    <h4>Average Cost per Hire</h4>
    <ul>
        <li><strong>2019:</strong> $4,129</li>
        <li><strong>2023:</strong> $4,700 (14% increase)</li>
    </ul>
    <h4>Factors Influencing Cost</h4>
    <ol>
        <li><strong>Company Size:</strong> Larger companies can spread operational costs among a greater number of hires.</li>
        <li><strong>Industry:</strong> Certain industries, such as cybersecurity, engineering, or nursing, experience talent shortages, increasing hiring costs.</li>
        <li><strong>Location:</strong> Hiring costs vary by geographic location.</li>
    </ol>
    <h3>Types of Costs</h3>
    <h4>Direct Costs</h4>
    <ul>
        <li><strong>Recruitment:</strong> Job postings, recruitment agency fees, candidate tracking software.</li>
        <li><strong>Selection:</strong> Tests, interviews, candidate travel.</li>
        <li><strong>Onboarding:</strong> Training, materials, existing employee time.</li>
    </ul>
    <h4>Indirect Costs</h4>
    <ul>
        <li><strong>Employee Time:</strong> Time employees spend on the hiring process, such as reviewing resumes and conducting interviews.</li>
        <li><strong>Productivity Loss:</strong> Productivity loss incurred when a position is vacant.</li>
        <li><strong>Turnover Costs:</strong> Costs associated with hiring a new employee to replace a departing one.</li>
    </ul>
    <p>This analysis provides a deeper understanding of the cost of hiring an employee in 2024 and the different factors influencing this cost. Understanding these aspects is crucial for strategic decision-making in human resource management and financial planning for companies.</p>
    <p>Source: <a href="https://toggl.com/blog/cost-of-hiring-an-employee">https://toggl.com/blog/cost-of-hiring-an-employee</a></p>
    <h2>Data and Methodology</h2>
    <h3>Dataset</h3>
    <p>The data used in this analysis were obtained from <a href="https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset">https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset</a>, containing relevant employee information, including demographic characteristics, employment history, performance evaluations, among others.</p>
    <h3>Data Preprocessing</h3>
    <p>Before training predictive models, an exhaustive data preprocessing process was performed, including data cleaning, handling categorical variables, managing missing values, and feature scaling.</p>
    <h2>Development of Predictive Model</h2>
    <h3>Feature Selection</h3>
    <p>The most relevant categorical variables for predicting employee resignations were carefully selected. Various machine learning methodologies were explored and evaluated, including Random Forest, Logistic Regression, and Deep Learning. Each of these techniques was applied with the aim of capturing the complexity and diversity of the data, thus providing a comprehensive approach to building three robust and accurate predictive models.</p>
    <h3>Model Training</h3>
    <p>Several machine learning models, including Logistic Regression, Random Forests, and Deep Learning, were trained using the training dataset.</p>
    <h2>Model Evaluation</h2>
    <p>The models were evaluated using metrics such as accuracy, recall, and F1-score. A detailed analysis of the confusion matrix was conducted to assess the model's performance in predicting employee resignations.</p>
    <h2>Conclusion</h2>
    <p>After a thorough evaluation of the three predictive models, the following conclusions were reached:</p>
    <p>To evaluate the performance of each model, key metrics such as <strong>Precision</strong>, <strong>Recall</strong>, <strong>F1-Score</strong>, and <strong>Accuracy</strong> were used. The results for predicting employees who are likely to resign ("Yes" class) are summarized below:</p>
    <table>
        <thead>
            <tr>
                <th>Métrica</th>
                <th>Regresión Logística</th>
                <th>Random Forest</th>
                <th>Deep Learning</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Precisión</td>
                <td>0.81</td>
                <td>1.00</td>
                <td>0.82</td>
            </tr>
            <tr>
                <td>Recall</td>
                <td>0.44</td>
                <td>0.28</td>
                <td>0.61</td>
            </tr>
            <tr>
                <td>F1-Score</td>
                <td>0.57</td>
                <td>0.44</td>
                <td>0.70</td>
            </tr>
            <tr>
                <td><strong>Exactitud General</strong></td>
                <td><strong>0.89</strong></td>
                <td><strong>0.87</strong></td>
                <td><strong>0.89</strong></td>
            </tr>
        </tbody>
    </table>
    <h3>Analysis of the Models:</h3>
    <ul>
        <li><strong>Random Forest:</strong> Despite its perfect precision, its very low recall (0.28) indicates that it fails to identify the majority of employees who are about to leave, making it less practical for retention purposes.</li>
        <li><strong>Logistic Regression:</strong> Offers a decent balance of metrics but is ultimately outperformed by the Deep Learning model.</li>
        <li><strong>Deep Learning (Neural Network):</strong> This model stands out as the <strong>best performer</strong>. It achieves the highest <strong>F1-Score (0.70)</strong> and the highest <strong>Recall (0.61)</strong>, meaning it correctly identifies 61% of employees who are at risk of leaving. This balance makes it the most effective tool for HR to take proactive retention measures.</li>
    </ul>
    <h3>Final Recommendation:</h3>
    <p>The <strong>Deep Learning model is the recommended choice</strong> for predicting employee resignation in this context. Its superior ability to identify at-risk employees (high recall) without a significant compromise in precision provides the most actionable insights for retaining valuable talent.</p>

</body>
</html>

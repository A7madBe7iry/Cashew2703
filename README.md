<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# creative AI

Final project for the Building AI course

## Summary

Artificial intelligence (AI) plays a critical role in public health, offering various applications such as disease surveillance and early warning systems, predictive modeling, personalized health guidance, and efficient public health data analysis. It helps identify health trends and patterns, improve the allocation of health resources, and advance health interventions and treatments, including vaccine development and precision medicine. AI has also proven to be effective in managing pandemics, particularly COVID-19, and will be a vital tool for future pandemic preparedness.


## Background

Artificial intelligence can automate routine tasks, thus freeing healthcare professionals to focus on more complex tasks. This can significantly improve the efficiency of public health operations. Providing accurate and timely data analysis, AI can support better public health decisions. This can lead to more effective interventions and better health outcomes. AI helps us provide personalized health advice and treatment, which may lead to better health outcomes.




## How is it used?

Artificial intelligence can examine a wide range of social data sources such as hospital social records or environmental data to detect disease outbreaks. It can analyze this data in real time, allowing early detection and rapid response to potential health crises. Providing personalized health assessments based on an individual's medical history and lifestyle factors. This allows early intervention and prevention measures tailored to individual health profiles. AI algorithms help manage the allocation of hospital beds or distribute healthcare resources efficiently during crises, as happened during the COVID-19 pandemic.

https://www.google.com/url?sa=i&url=https%3A%2F%2Fm-quality.net%2F%3Fp%3D44447&psig=AOvVaw1bRkRPv-kNzzrt1dFM3LHB&ust=1695156350399000&source=images&cd=vfe&opi=89978449&ved=0CBAQjRxqFwoTCND_0uuDtYEDFQAAAAAdAAAAABAE
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
my data came from https://webmedy.com/blog/ar/ai-public-health/
and i collected it by myself

## Challenges

The rapid development and implementation of artificial intelligence in public health presents regulatory challenges. Existing regulatory frameworks for health technologies often do not fully cover AI-specific issues. For example, how should we organize an AI system that is constantly learning and updating over time? How can we ensure the effectiveness and safety of AI applications in health? These questions highlight the need for dynamic, responsive and comprehensive regulatory mechanisms.... and AI systems are only as unbiased as the data they are trained on. If the training data is skewed or biased, AI models can perpetuate and amplify these biases. For example, if health data comes mostly from a specific demographic, the AI ​​system may fail to perform effectively relative to other demographic groups, leading to unequal health outcomes....

## What next?

Artificial intelligence will likely be an integral part of the future of telemedicine, making healthcare more accessible and less burdensome on healthcare systems. Furthermore, as AI algorithms become more advanced, they can play a role in health policy making by analyzing complex data to provide insights into the potential impacts of different policies.
AI can also be combined with other emerging technologies such as blockchain to improve data security, or with Internet of Things (IoT) devices for real-time health monitoring and disease prediction. For example, wearable IoT devices can constantly collect health data, and AI can analyze this data to predict potential health problems before they become serious.


## Acknowledgments

webmedy and University of Helsinki for creating Elements of AI and Building AI

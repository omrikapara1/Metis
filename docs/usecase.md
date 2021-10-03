## Learning
The term "Learnware" was originally created by teacher Zhou Zhihua from Nanjing University. Learnware = model + specification, which has the characteristics of reusability, evolvement and understanding.
Many people may have established similar models in their applications, and they are also willing to find a place to share these models. In this way, if a new user wants an application, he may not need to create one himself, but first go to the "learningware" market to find out if there is a suitable one, and use it directly or after modification. The learningware is built on the basis of experts, so it is easier to get expert-level results, and because the shared models are models, the problems of data leakage and privacy leakage are avoided.

## Operation and maintenance
"Operation and maintenance learningware" is also called AI operation and maintenance components, similar to APIs or public libraries in programs, but APIs and public libraries do not contain specific business data, but only a certain algorithm or logic, and AI operation and maintenance components are used in On the basis of similar API, it also has the "memory" ability to intelligently solve a certain operation and maintenance scene, and save the intelligent rules for processing this scene in this component. This intelligent rule is learned from a certain amount of data, and has the characteristics of "reusable", "evolvable", and "understandable". It can not only share the algorithm model trained by experts using data, but also protect the data. And privacy

## Application case scenario

The time series anomaly detection software has been polished by massive monitoring data, and has a wide range of applications in the fields of anomaly detection and operation, maintenance, monitoring and alarming.

![time_series_detector](images/time_series_detector.png)

### Features

Time series anomaly detection software：

* Anomaly detection API：Provide rate value detection and quantity value detection API interface，Detect time series

Time series anomaly detection software support system：

* Feature extraction: provide the extraction function of three types of features (statistical features, fitting features, classification features), feature dimensions 90+; support for adding custom features
* Abnormal query: the time series (only abnormal) detected by API is stored in the database, providing management functions, paging query, retrieval, zooming, etc.
* Marking: Provide the function of marking and marking, marking/unmarking as positive and negative samples, and the samples are automatically transferred to the sample library after marking
* Sample management: Provide sample management functions, search, icon, edit, delete, import and other functions
* Model management: Provide model management functions and support custom model training

### Application data scenario

* Operating system data: It is suitable for detecting basic monitoring data at the operating system level, such as CPU, memory, disk, traffic, packet volume, etc.
* Application data: It is suitable for detecting the time series data recorded during the running of the application, such as the amount of reading and writing, the amount of calls, and custom monitoring indicators.
* KPI indicator data: suitable for testing business KPI data, such as key business indicators such as transaction volume, revenue value, online number, success rate, and failure volume.


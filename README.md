# Security Architecture for Tech Solutions Inc.

**Author**: Osamudiamen Eweka  
**Course**: CYB-653-Z1 Securing and Defending Networks  
**Instructor**: Dr. Donnie Wendt  
**Institution**: Utica University

## Overview

This paper presents a security architecture for Tech Solutions Inc., a mid-sized company that handles sensitive data and provides online products and services. The architecture is designed to support the company's transition to a zero-trust model while also protecting legacy on-premises applications using a defense-in-depth strategy. The plan addresses diverse security needs for legacy on-premises applications, cloud-based applications, SaaS products, and on-premises email services.

## Table of Contents

1. Executive Summary
2. Introduction
3. Legacy On-Premises Applications
4. Cloud-Based Applications
5. SaaS Applications
6. On-Premises Email Services
7. Logical Architecture Drawing
8. Conclusion
9. References

## Key Sections

### 1. Executive Summary
Tech Solutions Inc. handles sensitive data, including Personally Identifiable Information (PII), and is transitioning to a zero-trust architecture (ZTA) while supporting legacy on-premises applications with a defense-in-depth strategy. The security architecture includes measures such as network segmentation, firewalls, Intrusion Detection/Prevention Systems (IDPS), identity and access management (IAM), multi-factor authentication (MFA), encryption, and continuous monitoring. These measures are tailored to secure the company’s cloud-based applications, SaaS products, and on-premises email services, ensuring robust protection and compliance with regulatory requirements.

### 2. Introduction
Tech Solutions Inc. provides online products and services, and its infrastructure includes a mix of legacy on-premises applications, cloud-based applications hosted by a major cloud provider, and SaaS products for internal processes. The company operates in a hybrid environment, requiring secure access from both remote and office locations. This paper outlines the security architecture needed to address these diverse needs with a focus on implementing zero-trust principles for cloud-based and SaaS applications, while maintaining a defense-in-depth strategy for legacy systems.

### 3. Legacy On-Premises Applications
Legacy on-premises applications are critical to Tech Solutions Inc.'s operations and require a traditional defense-in-depth strategy. Key security measures include network segmentation, firewalls, IDPS, role-based access control (RBAC), and regular audits. These measures ensure that legacy applications are isolated, monitored, and protected from external and internal threats.

### 4. Cloud-Based Applications
Cloud-based applications require a zero-trust approach that includes IAM with MFA, encryption of data in transit and at rest, micro-segmentation, and continuous monitoring using cloud-native security tools. These measures help secure customer-facing products and services while ensuring that only authorized users can access sensitive data.

### 5. SaaS Applications
SaaS applications for internal business functions such as HR and finance are accessed securely using VPNs or Secure Access Service Edge (SASE) with conditional access policies. Endpoint security measures, such as antivirus and regular patching, are also implemented to protect against malware and other threats.

### 6. On-Premises Email Services
On-premises email services are protected using advanced email filtering, encryption, and regular security awareness training for employees to defend against phishing, malware, and other email-based threats.

### 7. Logical Architecture Drawing
The logical architecture for Tech Solutions Inc. illustrates the hybrid environment that integrates zero-trust principles for cloud-based and SaaS applications with a defense-in-depth strategy for legacy systems. The diagram includes key components such as firewalls, VPN servers, IDPS, network segmentation, and secure access gateways to ensure comprehensive security across the company’s infrastructure.

### 8. Conclusion
The proposed security architecture for Tech Solutions Inc. balances the requirements of a zero-trust model for cloud-based and SaaS applications with a traditional defense-in-depth strategy for legacy on-premises applications. By implementing these measures, Tech Solutions Inc. can ensure robust protection of its sensitive data and secure access to its products and services. Continuous monitoring, advanced security tools, and regular employee training further enhance the company's resilience against evolving cyber threats.

## References

- Bhardwaj, A., & Goundar, S. (2017). *Security challenges for cloud-based email infrastructure*. Network Security, 2017(11), 8-11.
- Dhiman, P., Saini, N., Gulzar, Y., Turaev, S., Kaur, A., Nisa, K. U., & Hamid, Y. (2024). *A review and comparative analysis of relevant approaches of zero trust network model*. Sensors, 24(4), 1328. https://doi.org/10.3390/s24041328
- FORCE, J. T., & Initiative, T. (2013). *Security and privacy controls for federal information systems and organizations*. NIST Special Publication, 800(53), 8-13.
- Rose, S., Borchert, O., Mitchell, S., & Connelly, S. (2020). *Zero trust architecture*. National Institute of Standards and Technology. https://doi.org/10.6028/NIST.SP.800-207
- Rukhsara, L., Aklam, F., Nawer, T., Chauhan, N. S., & Islam, M. N. (2016, May). *A conceptual cloud-based model for developing e-commerce applications in context of Bangladesh*. IEEE 5th International Conference on Informatics, Electronics, and Vision (ICIEV), 117-121. IEEE.
- Samaniego, M., & Deters, R. (2018). *Zero-Trust Hierarchical Management in IoT*. IEEE International Congress on Internet of Things. https://doi.org/10.1109/ICIOT.2018.00019

For the complete list of references, please refer to the full report.

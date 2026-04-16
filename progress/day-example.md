# 📅 Day x Example – Node Selectors

## ✔ What I did
- Reviewed Kubernetes Node Selectors concept
- Labeled a node using kubectl:
  kubectl label nodes <node-name> disktype=ssd
- Created a Pod using nodeSelector to control scheduling
- Verified pod placement on the correct node

## 🧪 Technical Implementation
- Applied node labels to influence scheduling decisions
- Defined nodeSelector in Pod spec to enforce placement constraints
- Tested scheduling behavior by modifying node labels

## ❌ Issues / Problems
- Initial mismatch between node label key and selector caused pod to remain pending
- Resolved by correcting label key-value pair

## 🧠 Notes (Technical Understanding)
- Node Selector is a simple scheduling constraint based on exact label matching
- If label does not match exactly, Pod will not be scheduled
- This is a basic but strict scheduling mechanism in Kubernetes

## 📦 Files Created
- /k8s/scheduling/node-selector.yaml

## ⏱ Time spent
2h (lab + debugging)

## 🔁 Improvements for tomorrow
- Practice Taints & Tolerations
- Improve speed in kubectl debugging commands

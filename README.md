# MyFoodGRS
MyFoodGRS data

# Anticipating Eating Preferences in Group Decision Making

This repository contains data and supplementary materials for the paper "Anticipating Eating Preferences in Group Decision Making" presented at the 32nd ACM Conference on User Modeling, Adaptation and Personalization (UMAP Adjunct ’24).

## Abstract

In a decision-making scenario, an individual, who is part of a group may need to independently make a choice for an item that will be consumed by the group. In prior research on restaurant recommendation, we have identified two primary tasks for the organizer of a lunch/dinner event, who makes the decision of selecting a proper restaurant for the group: anticipating the group members' preferences for the restaurant to be selected for the event, in order to enter their preferences in the recommender system, and reconciling incompatible preferences, if they arise in the elicitation phase. To support the first task, we augmented a group recommender system with a machine learning model that predicts group members' food preferences, about dishes that can be consumed in the restaurant, based on other available information about them (demographics and preferred cuisine). However, in a user study, we found that supporting functionality to be not effective in improving the quality of the choices made by the organizer.

In this paper, we investigate the causes of this poor performance. We analyze the possibility that the poor performance may relate to: the deployed ML models used for food preference prediction, the amount of data about food preferences used for training the ML model, and the complexity of the preference prediction task. The results of our experiments suggest that neither the ML model nor the scarcity of the preference data is responsible for the observed poor utility of the implemented preference recalling function. While a user study seems to confirm the impossibility of accurately predicting food preferences from the considered user's features (demographics and preferred cuisine).

## Files

- `actual_users_preferences.csv`: Actual preferences of real users.
- `prediction_of_actual_users_preferences_by_human.csv`: Predictions of human experts on actual users' preferences.

## Venue Information

- **Authors**: Hanif Emamgholizadeh, Amra Delić, Francesco Ricci
- **Conference**: 32nd ACM Conference on User Modeling, Adaptation and Personalization (UMAP Adjunct ’24)
- **Date**: July 1–4, 2024
- **Location**: Cagliari, Italy
- **Publisher**: ACM, New York, NY, USA
- **DOI**: [10.1145/3631700.3664894](https://doi.org/10.1145/3631700.3664894)

## Citation

If you use this dataset or find our work useful, please cite our paper:
@inproceedings{emamgholizadeh2024anticipating,
title={Anticipating Eating Preferences in Group Decision Making},
author={Emamgholizadeh, Hanif and Delić, Amra and Ricci, Francesco},
booktitle={Adjunct Proceedings of the 32nd ACM Conference on User Modeling, Adaptation and Personalization},
year={2024},
organization={ACM}
}

# transaction_framework

## Tables

| Name | Columns | Comment | Type |
| ---- | ------- | ------- | ---- |
| [_view_all_used_parameter_ids](_view_all_used_parameter_ids.md) | 1 | VIEW | VIEW |
| [_view_i18n__all_invalids](_view_i18n__all_invalids.md) | 8 | VIEW | VIEW |
| [_view_i18n__all_invalids__match_found](_view_i18n__all_invalids__match_found.md) | 10 | VIEW | VIEW |
| [_view_i18n__all_occurrences](_view_i18n__all_occurrences.md) | 8 | VIEW | VIEW |
| [_view_i18n__to_translate](_view_i18n__to_translate.md) | 8 | VIEW | VIEW |
| [_view_i18n__unused_strings](_view_i18n__unused_strings.md) | 7 | VIEW | VIEW |
| [_view_parameters__all_invalids](_view_parameters__all_invalids.md) | 7 | VIEW | VIEW |
| [_view_parameters_all_occurences](_view_parameters_all_occurences.md) | 5 | VIEW | VIEW |
| [_view_parameters_duplicate](_view_parameters_duplicate.md) | 30 | VIEW | VIEW |
| [_view_parameters_unused](_view_parameters_unused.md) | 30 | VIEW | VIEW |
| [_view_responses__unused](_view_responses__unused.md) | 10 | VIEW | VIEW |
| [_view_trxn_request](_view_trxn_request.md) | 25 | VIEW | VIEW |
| [_view_trxn_response](_view_trxn_response.md) | 16 | VIEW | VIEW |
| [_view_trxn_response_chains](_view_trxn_response_chains.md) | 24 | VIEW | VIEW |
| [brand_categories](brand_categories.md) | 5 |  | BASE TABLE |
| [brand_products](brand_products.md) | 7 |  | BASE TABLE |
| [chain_behaviors](chain_behaviors.md) | 3 |  | BASE TABLE |
| [confirm_submit_master](confirm_submit_master.md) | 3 |  | BASE TABLE |
| [connect_agreement](connect_agreement.md) | 3 |  | BASE TABLE |
| [display_media](display_media.md) | 2 | Which media to show a response-parameter on? Eg: screen, paper, both, none, etc | BASE TABLE |
| [doodles](doodles.md) | 7 |  | BASE TABLE |
| [highlight_master](highlight_master.md) | 3 |  | BASE TABLE |
| [i18n_lang_strings](i18n_lang_strings.md) | 8 |  | BASE TABLE |
| [i18n_lang_strings_app](i18n_lang_strings_app.md) | 10 |  | BASE TABLE |
| [interaction_behaviors](interaction_behaviors.md) | 3 |  | BASE TABLE |
| [interaction_categories](interaction_categories.md) | 5 |  | BASE TABLE |
| [interaction_chain_input_parameters](interaction_chain_input_parameters.md) | 8 |  | BASE TABLE |
| [interaction_chain_parameter_sources](interaction_chain_parameter_sources.md) | 3 |  | BASE TABLE |
| [interaction_chains](interaction_chains.md) | 20 |  | BASE TABLE |
| [interaction_group_links](interaction_group_links.md) | 9 |  | BASE TABLE |
| [interactions](interactions.md) | 43 |  | BASE TABLE |
| [list_elements](list_elements.md) | 12 |  | BASE TABLE |
| [parameter_separator_types_master](parameter_separator_types_master.md) | 3 |  | BASE TABLE |
| [parameter_types](parameter_types.md) | 3 | This tables stores possible category of parameters. | BASE TABLE |
| [parameters](parameters.md) | 32 |  | BASE TABLE |
| [request_expressions](request_expressions.md) | 7 | Use mathematical expressions using values of other parameters to calculate visibility, enable/disable or new value of other parameters | BASE TABLE |
| [request_structure](request_structure.md) | 29 |  | BASE TABLE |
| [response_interaction_map](response_interaction_map.md) | 4 |  | BASE TABLE |
| [response_parameter_groups](response_parameter_groups.md) | 6 |  | BASE TABLE |
| [response_status](response_status.md) | 3 |  | BASE TABLE |
| [response_structure](response_structure.md) | 10 |  | BASE TABLE |
| [responses](responses.md) | 10 |  | BASE TABLE |
| [role_interaction_map](role_interaction_map.md) | 8 |  | BASE TABLE |
| [text_case_types](text_case_types.md) | 3 |  | BASE TABLE |
| [uri_root_master](uri_root_master.md) | 3 |  | BASE TABLE |

## Relations

![er](schema.png)

---

> Generated by [tbls](https://github.com/k1LoW/tbls)

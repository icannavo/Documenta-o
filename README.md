Permite a Instituição Fiduciária realizar, junto ao Agente Operador do FGTS, o cancelamento de uma reserva de valores de saque 
aniversário do Trabalhador utilizados como garantia para uma operação fiduciária
ATENÇÃO: A operação só poderá ser desaverbada se ela já tiver sido cancelada.
Request
ENDPOINT /debt/{debt_key}//cancel_permanently
METHOD POST
Path Params:
Key Value Description
debt_key 95ba572e-b8d2-43db-94b9-8c4a0405e3bc Debt key da operação que esta sendo 
cancelada.
Response (200)
ENDPOINT /debt/{debt_key}//cancel_permanently
METHOD POST
Body:
{
 "data": {
 "additional_iof": 0.956498,
 "annual_cet": 41.5826,
 "assignment_amount": 251.71,
 "base_iof": 5.38721386,
 "borrower": {
 "document_number": "0000000000",
 "name": "Andre Luis Souto de Souza"
 },
 "cet": 2.94,
 "collaterals": [
 {
 "collateral_constituted": false,
 "collateral_data": {
 "document_number": "00000000000",
 "error_message": "None",
 "periods": [
 {
 "amount": 116.48,
 "due_date": "2023-04-01"
 },
 {
 "amount": 81.53,
 "due_date": "2024-04-01"
 },
 {
 "amount": 57.07,
 "due_date": "2025-04-01"
 },
 {
 "amount": 39.95,
 "due_date": "2026-04-01"
 },
 {
 "amount": 37.29,
 "due_date": "2027-04-01"
 },
 {
 "amount": 27.96,
 "due_date": "2028-04-01"
 },
 {
 "amount": 13.99,
 "due_date": "2029-04-01"
 },
 {
 "amount": 6.99,
 "due_date": "2030-04-01"
 },
 {
 "amount": 3.49,
 "due_date": "2031-04-01"
 },
 {
 "amount": 3.6,
 "due_date": "2032-04-01"
 }
 ],
 "protocol_number": null,
 "reservation_request_closure_status": null,
 "reservation_request_closure_status_translation": null,
 "reservation_request_key": "11e904ad-1e7c-46c7-9e15-
16d3650670bd",
 "reservation_request_status": "pending",
 "reservation_request_status_translation": "Em Teimosinha"
 },
 "collateral_key": "7686f240-329b-4ef5-8956-914c05cbd445",
 "collateral_type": "fgts_balance",
 "created_at": "2022-12-19T15:52:32",
 "external_key": "11e904ad-1e7c-46c7-9e15-16d3650670bd",
 "percentage": 1,
 "updated_at": "2022-12-20T21:09:27.573223"
 }
 ],
 "contract": {
 "number": "0003296996/ALS-R",
 "urls": [
 "https://storage.googleapis.com/live-doc-api/documents/0e2d7181-
799c-4134-af18-2a9ffb14da57/HUBCREDFINTECHLTDAANDRE_LUIS_SOUTO_DE_SOUZA-CCB-0003296996-20221219155233.pdf"
 ]
 },
 "contract_fee_amount": 2.46,
 "contract_fees": [
 {
 "fee_amount": 1.26,
 "fee_type": "tac"
 },
 {
 "fee_amount": 1.2,
 "fee_type": "ted_fee"
 }
 ],
 "disbursed_issue_amount": 211.45,
 "entry": null,
 "external_contract_fee_amount": 31.46,
 "external_contract_fees": [
 {
 "description": null,
 "fee_amount": 15.1,
 "fee_type": "tac",
 "net_fee_amount": 12.95,
 "rebate_bank_account": {
 "account_branch": "1",
 "account_digit": "5",
 "account_number": "1000398",
 "created_at": "2022-12-19T15:52:32",
 "document_number": "000000000000",
 "financial_institutions": {
 "code_number": 329,
 "is_active": true,
 "is_pix_participant": true,
 "ispb": 32402502,
 "name": "QI SCD S.A."
 },
 "financial_institutions_code_number": 329,
 "name": "QI SOCIEDADE DE CREDITO DIRETO SA"
 },
 "tax_amount": 2.15
 },
 {
 "description": null,
 "fee_amount": 16.36,
 "fee_type": "tac",
 "net_fee_amount": 14.03,
 "rebate_bank_account": {
 "account_branch": "1",
 "account_digit": "1",
 "account_number": "1000418",
 "created_at": "2022-12-19T15:52:32",
 "document_number": "000000000000",
 "financial_institutions": {
 "code_number": 329,
 "is_active": true,
 "is_pix_participant": true,
 "ispb": 32402502,
 "name": "QI SCD S.A."
 },
 "financial_institutions_code_number": 329,
 "name": "QI SOCIEDADE DE CREDITO DIRETO SA"
 },
 "tax_amount": 2.33
 },
 {
 "description": null,
 "fee_amount": 0,
 "fee_type": "spread",
 "net_fee_amount": 0,
 "rebate_bank_account": null,
 "tax_amount": 0
 }
 ],
 "installments": [
 {
 "accrual_reference_date": null,
 "additional_costs": [],
 "advanced_paid_amount": 0,
 "bank_slip_key": null,
 "business_due_date": "2023-04-03",
 "calendar_days": 103,
 "digitable_line": null,
 "due_date": "2023-04-01",
 "due_interest": 0,
 "due_principal": 251.71,
 "fine_amount": null,
 "has_interest": true,
 "installment_key": "9badede6-9db0-45d9-9797-9b1459eb4a38",
 "installment_number": 1,
 "installment_payment": [],
 "installment_status": "canceled",
 "installment_type": "principal",
 "original_due_principal": 251.71,
 "original_pre_fixed_amount": 16.57,
 "original_principal_amortization_amount": 99.91,
 "original_total_amount": 116.48,
 "paid_amount": 0,
 "paid_at": null,
 "post_fixed_amount": null,
 "pre_fixed_amount": 16.57,
 "principal_amortization_amount": 99.91,
 "qr_code_key": null,
 "qr_code_url": null,
 "renegotiation_proposal_key": null,
 "tax_amount": 0.84383986,
 "total_accrual_amount": null,
 "total_amount": 116.48,
 "total_paid_amount": 0,
 "workdays": 72
 },
 {
 "accrual_reference_date": null,
 "additional_costs": [],
 "advanced_paid_amount": 0,
 "bank_slip_key": null,
 "business_due_date": "2024-04-01",
 "calendar_days": 366,
 "digitable_line": null,
 "due_date": "2024-04-01",
 "due_interest": 0,
 "due_principal": 151.8,
 "fine_amount": null,
 "has_interest": true,
 "installment_key": "c3c86b8b-5af8-47de-a77a-ef8622955219",
 "installment_number": 2,
 "installment_payment": [],
 "installment_status": "canceled",
 "installment_type": "principal",
 "original_due_principal": 151.8,
 "original_pre_fixed_amount": 38.58,
 "original_principal_amortization_amount": 42.95,
 "original_total_amount": 81.53,
 "paid_amount": 0,
 "paid_at": null,
 "post_fixed_amount": null,
 "pre_fixed_amount": 38.58,
 "principal_amortization_amount": 42.95,
 "qr_code_key": null,
 "qr_code_url": null,
 "renegotiation_proposal_key": null,
 "tax_amount": 1.2854935,
 "total_accrual_amount": null,
 "total_amount": 81.53,
 "total_paid_amount": 0,
 "workdays": 248
 },
 {
 "accrual_reference_date": null,
 "additional_costs": [],
 "advanced_paid_amount": 0,
 "bank_slip_key": null,
 "business_due_date": "2025-04-01",
 "calendar_days": 365,
 "digitable_line": null,
 "due_date": "2025-04-01",
 "due_interest": 0,
 "due_principal": 108.85,
 "fine_amount": null,
 "has_interest": true,
 "installment_key": "5c3aa86f-bb17-4e60-85d0-64cfc8082332",
 "installment_number": 3,
 "installment_payment": [],
 "installment_status": "canceled",
 "installment_type": "principal",
 "original_due_principal": 108.85,
 "original_pre_fixed_amount": 27.58,
 "original_principal_amortization_amount": 29.49,
 "original_total_amount": 57.07,
 "paid_amount": 0,
 "paid_at": null,
 "post_fixed_amount": null,
 "pre_fixed_amount": 27.58,
 "principal_amortization_amount": 29.49,
 "qr_code_key": null,
 "qr_code_url": null,
 "renegotiation_proposal_key": null,
 "tax_amount": 0.8826357,
 "total_accrual_amount": null,
 "total_amount": 57.07,
 "total_paid_amount": 0,
 "workdays": 254
 },
 {
 "accrual_reference_date": null,
 "additional_costs": [],
 "advanced_paid_amount": 0,
 "bank_slip_key": null,
 "business_due_date": "2026-04-01",
 "calendar_days": 365,
 "digitable_line": null,
 "due_date": "2026-04-01",
 "due_interest": 0,
 "due_principal": 79.36,
 "fine_amount": null,
 "has_interest": true,
 "installment_key": "e3e01865-bd87-4934-bce4-52fcae82c30e",
 "installment_number": 4,
 "installment_payment": [],
 "installment_status": "canceled",
 "installment_type": "principal",
 "original_due_principal": 79.36,
 "original_pre_fixed_amount": 20.11,
 "original_principal_amortization_amount": 19.84,
 "original_total_amount": 39.95,
 "paid_amount": 0,
 "paid_at": null,
 "post_fixed_amount": null,
 "pre_fixed_amount": 20.11,
 "principal_amortization_amount": 19.84,
 "qr_code_key": null,
 "qr_code_url": null,
 "renegotiation_proposal_key": null,
 "tax_amount": 0.5938112,
 "total_accrual_amount": null,
 "total_amount": 39.95,
 "total_paid_amount": 0,
 "workdays": 253
 },
 {
 "accrual_reference_date": null,
 "additional_costs": [],
 "advanced_paid_amount": 0,
 "bank_slip_key": null,
 "business_due_date": "2027-04-01",
 "calendar_days": 365,
 "digitable_line": null,
 "due_date": "2027-04-01",
 "due_interest": 0,
 "due_principal": 59.52,
 "fine_amount": null,
 "has_interest": true,
 "installment_key": "a0f2a23f-0766-4912-a0de-7b84c1df1c9e",
 "installment_number": 5,
 "installment_payment": [],
 "installment_status": "canceled",
 "installment_type": "principal",
 "original_due_principal": 59.52,
 "original_pre_fixed_amount": 15.08,
 "original_principal_amortization_amount": 22.21,
 "original_total_amount": 37.29,
 "paid_amount": 0,
 "paid_at": null,
 "post_fixed_amount": null,
 "pre_fixed_amount": 15.08,
 "principal_amortization_amount": 22.21,
 "qr_code_key": null,
 "qr_code_url": null,
 "renegotiation_proposal_key": null,
 "tax_amount": 0.6647453,
 "total_accrual_amount": null,
 "total_amount": 37.29,
 "total_paid_amount": 0,
 "workdays": 249
 },
 {
 "accrual_reference_date": null,
 "additional_costs": [],
 "advanced_paid_amount": 0,
 "bank_slip_key": null,
 "business_due_date": "2028-04-03",
 "calendar_days": 366,
 "digitable_line": null,
 "due_date": "2028-04-01",
 "due_interest": 0,
 "due_principal": 37.31,
 "fine_amount": null,
 "has_interest": true,
 "installment_key": "a0916b23-c193-4a61-8850-1fbae73440d5",
 "installment_number": 6,
 "installment_payment": [],
 "installment_status": "canceled",
 "installment_type": "principal",
 "original_due_principal": 37.31,
 "original_pre_fixed_amount": 9.48,
 "original_principal_amortization_amount": 18.48,
 "original_total_amount": 27.96,
 "paid_amount": 0,
 "paid_at": null,
 "post_fixed_amount": null,
 "pre_fixed_amount": 9.48,
 "principal_amortization_amount": 18.48,
 "qr_code_key": null,
 "qr_code_url": null,
 "renegotiation_proposal_key": null,
 "tax_amount": 0.5531064,
 "total_accrual_amount": null,
 "total_amount": 27.96,
 "total_paid_amount": 0,
 "workdays": 253
 },
 {
 "accrual_reference_date": null,
 "additional_costs": [],
 "advanced_paid_amount": 0,
 "bank_slip_key": null,
 "business_due_date": "2029-04-02",
 "calendar_days": 365,
 "digitable_line": null,
 "due_date": "2029-04-01",
 "due_interest": 0,
 "due_principal": 18.83,
 "fine_amount": null,
 "has_interest": true,
 "installment_key": "aeda565d-e743-408d-bbff-32374eadd02d",
 "installment_number": 7,
 "installment_payment": [],
 "installment_status": "canceled",
 "installment_type": "principal",
 "original_due_principal": 18.83,
 "original_pre_fixed_amount": 4.77,
 "original_principal_amortization_amount": 9.22,
 "original_total_amount": 13.99,
 "paid_amount": 0,
 "paid_at": null,
 "post_fixed_amount": null,
 "pre_fixed_amount": 4.77,
 "principal_amortization_amount": 9.22,
 "qr_code_key": null,
 "qr_code_url": null,
 "renegotiation_proposal_key": null,
 "tax_amount": 0.2759546,
 "total_accrual_amount": null,
 "total_amount": 13.99,
 "total_paid_amount": 0,
 "workdays": 247
 },
 {
 "accrual_reference_date": null,
 "additional_costs": [],
 "advanced_paid_amount": 0,
 "bank_slip_key": null,
 "business_due_date": "2030-04-01",
 "calendar_days": 365,
 "digitable_line": null,
 "due_date": "2030-04-01",
 "due_interest": 0,
 "due_principal": 9.61,
 "fine_amount": null,
 "has_interest": true,
 "installment_key": "8a8dcf1a-40fb-4526-b7ab-ae133c12b388",
 "installment_number": 8,
 "installment_payment": [],
 "installment_status": "canceled",
 "installment_type": "principal",
 "original_due_principal": 9.61,
 "original_pre_fixed_amount": 2.44,
 "original_principal_amortization_amount": 4.55,
 "original_total_amount": 6.99,
 "paid_amount": 0,
 "paid_at": null,
 "post_fixed_amount": null,
 "pre_fixed_amount": 2.44,
 "principal_amortization_amount": 4.55,
 "qr_code_key": null,
 "qr_code_url": null,
 "renegotiation_proposal_key": null,
 "tax_amount": 0.1361815,
 "total_accrual_amount": null,
 "total_amount": 6.99,
 "total_paid_amount": 0,
 "workdays": 251
 },
 {
 "accrual_reference_date": null,
 "additional_costs": [],
 "advanced_paid_amount": 0,
 "bank_slip_key": null,
 "business_due_date": "2031-04-01",
 "calendar_days": 365,
 "digitable_line": null,
 "due_date": "2031-04-01",
 "due_interest": 0,
 "due_principal": 5.06,
 "fine_amount": null,
 "has_interest": true,
 "installment_key": "10c9b5d0-0401-4e7c-b58e-635de70434c7",
 "installment_number": 9,
 "installment_payment": [],
 "installment_status": "canceled",
 "installment_type": "principal",
 "original_due_principal": 5.06,
 "original_pre_fixed_amount": 1.28,
 "original_principal_amortization_amount": 2.21,
 "original_total_amount": 3.49,
 "paid_amount": 0,
 "paid_at": null,
 "post_fixed_amount": null,
 "pre_fixed_amount": 1.28,
 "principal_amortization_amount": 2.21,
 "qr_code_key": null,
 "qr_code_url": null,
 "renegotiation_proposal_key": null,
 "tax_amount": 0.0661453,
 "total_accrual_amount": null,
 "total_amount": 3.49,
 "total_paid_amount": 0,
 "workdays": 253
 },
 {
 "accrual_reference_date": null,
 "additional_costs": [],
 "advanced_paid_amount": 0,
 "bank_slip_key": null,
 "business_due_date": "2032-04-01",
 "calendar_days": 366,
 "digitable_line": null,
 "due_date": "2032-04-01",
 "due_interest": 0,
 "due_principal": 2.85,
 "fine_amount": null,
 "has_interest": true,
 "installment_key": "663f8109-cca3-469a-855a-4f0294fb77ba",
 "installment_number": 10,
 "installment_payment": [],
 "installment_status": "canceled",
 "installment_type": "principal",
 "original_due_principal": 2.85,
 "original_pre_fixed_amount": 0.75,
 "original_principal_amortization_amount": 2.85,
 "original_total_amount": 3.6,
 "paid_amount": 0,
 "paid_at": null,
 "post_fixed_amount": null,
 "pre_fixed_amount": 0.75,
 "principal_amortization_amount": 2.85,
 "qr_code_key": null,
 "qr_code_url": null,
 "renegotiation_proposal_key": null,
 "tax_amount": 0.0853005,
 "total_accrual_amount": null,
 "total_amount": 3.6,
 "total_paid_amount": 0,
 "workdays": 253
 }
 ],
 "iof_charge_method": "financed",
 "issue_amount": 251.71,
 "net_external_contract_fee_amount": 26.98,
 "number_of_installments": 10,
 "prefixed_interest_rate": {
 "annual_rate": 0.25340149,
 "created_at": "2022-12-19T15:52:32",
 "daily_rate": 0.00061899,
 "interest_base": "calendar_days_365",
 "monthly_rate": 0.019
 },
 "requester_identifier_key": "93a47fc5-5969-42ff-bdbb-3c9e8ec58d35",
 "total_iof": 6.34,
 "total_pre_fixed_amount": 136.64
 },
 "event_datetime": "2022-12-20 21:09:28",
 "key": "93a47fc5-5969-42ff-bdbb-3c9e8ec58d35",
 "status": "canceled_permanently",
 "webhook_type": "debt"
}
Quando todas as reversões são executadas com sucesso, uma rotina é executada uma vez por dia, coletando o valor adequado e enviando 
para o fundo.
Response (400)
ENDPOINT /debt/{debt_key}/cancel_permanently
METHOD POST
Body:
{
 "data": "{\"title\": \"Bad Request\", \"description\": \"Operation 
with status {status} cannot be cancelled.\", \"translation\": \"Essa 
operação com {status} não permite cancelamento.\", \"extra_fields\": 
{}, \"code\": \"COP000245\"}"
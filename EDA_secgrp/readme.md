# campaign-finance-election-relationship

The task of this data science project will be to:
* first analyze if the data available on the finance of candidates
during campaign process has a relationship with the election outcome after voting

* Secondly, try to predict the outcome of election process from the expenditure of each candidiate

### Data description
The data used is an hosted kaggle dataset provided <a href="https://www.kaggle.com/danerbland/electionfinance">here</a>


*features of the dataset are explained below*

- can_id: candidate identification number
- can_nam: candidate name
- can_off: Office the candidate is campaigning for
  - P for presisency
  - H for House of assembly
- can_off_sta: state of the office
- can_off_dis: District of the office
- can_par_aff: candidate party affiliation
- can_inc_cha_ope_sea: candidate incubent challenger open seat
- can_str1: candidate street 1
- can_str2: candidate street 2
- can_cit: candidate city
- can_sta: candidate state
- can_zip: candidate zip code
- ind_ite_con: individual itemized contribution
- ind_uni_con: individual unitemized contribution
- ind_con: individual contribution
- par_com_con: party committee contribution
- oth_com_con: other committee contribution
- can_con: candidate contribution
- tot_con: total contribution
- tra_fro_oth_aut_com: Transfer From Other Auth Committee
- can_loa: candidate loan
- oth_loa: other loan
- tot_loa: total loan
- off_to_ope_exp: offset to operating expenditure
- off_to_fun: offset to fundraising
- off_to_leg_acc: offsets to legal accounting
- oth_rec: other receipts
- tot_rec: total receipts
- ope_exp: operating expenditure
- exe_leg_acc_dis: exempt legal accounting disburstment
- fun_dis: fundraising disburstment
- tra_to_oth_aut_com: transfer to other auth committee
- can_loa_rep: candidate loan repayment
- oth_loa_rep: other loan repayment
- oth_loa_rep: total loan repayment
- ind_ref: individual refund
- par_com_ref: party committee refund
- oth_com_ref: other committee refund
- tot_con_ref: total contribution refund
- oth_dis: other disbursement
- tot_dis: total disbursement
- cas_on_han_beg_of_per: cash on hand begining of per
- cas_on_han_clo_of_per: cash on hand closing of per
- net_con: net contribution
- net_ope_exp: net operating expenditure
- deb_owe_by_com: debt owed by committee
- deb_owe_to_com: debt owed to committee
- cov_sta_dat: coverage start date
- cov_end_dat: coverage end date
- winner: election winner
  - Y: yes
  - N: no
- votes: number of votes in favour of candidate

# Note: 
more novel data about the united states campaign to election process can be found <a href="https://www.fec.gov/data/browse-data/?tab=candidates">here</a>

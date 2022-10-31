# Recognition
HVite -T 1 -C etc/configuration -p -40 -s 6 -w etc/bigram -i recognized.txt -S etc/data_list -H hmm.txt etc/dictionary etc/hmm_list

# Confusion matrix
HResults -p -I etc/transcript etc/vocabulary recognized.txt

# Live
# HVite -C etc/configuration_live -p -40 -s 6 -w etc/bigram -H hmm.txt etc/dictionary etc/hmm_list

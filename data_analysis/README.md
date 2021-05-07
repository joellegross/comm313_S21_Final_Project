## Data analysis notebooks for COMM313 Final Project

* To explore my hypotheses I have conducted sentiment analysis with VADER, keyness analysis, KWIC analysis, and sentiment analysis with NRC Lexicon.

* I also conducted some exploratory analysis to descibe my corpora

* Here is an overview of what is in each file:

* ` description_of_corpora.ipynb`: Exploratory Analysis of Corpora

    * Describes number of tweets  in each corpus
    * Word Cloud depicting users in each corpus
    * Graphs of Top 10 users in each corpus
    * Number of Tweets per week from March 2020-March 2021
    * Peak Polarization analysis, defining the greatest differences between corpus, 3 days of the year


* ` sentiment_analysis_with_VADER.ipynb`: Sentiment Analysis with VADER
    
    * For Vaccine, Mask, Economy related words:
        * Plot of Sentiment Data over course of year
        * Peak Polarization Analysis
        * Difference in Means Analysis & Graph
        
* ` keyness_analysis.ipynb`: Keyness Analysis

     * For Mask, Vaccine, Economy Words
         * Log Likelihood Analysis
         * Graph of Log Likelihood Analysis
         
     * One-Word Lists, Bigram, Trigram Comparisons Across Corpora
         * One-Word Keyness Analysis for Liberal & Conservative Corpus
             * graphs of keyness analysis
         * Bigram Keyness Analysis for Liberal & Conservative Corpus
             * graphs of keyness analysis
         * Trigram Keyness Analysis for Liberal & Conservative Corpus
             * graphs of keyness analysis
         
* ` key_word_in_context.ipynb`: KWIC Analysis

     *   For Mask, Vaccine, Economy Words
         *  KWIC Analysis
     *  Other words KWIC Analysis

* ` sentiment_analysis_with_NRC_lexicons.ipynb`: Sentiment Analysis with NRC Lexicon

     *  For Mask, Vaccine, Economy Words
         * Sentiment Analysis with NRC Lexicon
         * Difference in Means & Graph
 
 * ` functions.ipynb`: functions file
         

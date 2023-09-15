# NatureMetrics - Bioinformatics Pipeline Developer Project

## Project

### Inputs

#### BAM

Input BAM can be obtained at [Tiny Bam](https://github.com/brainstorm/tiny-test-data/blob/master/wgs/mt.bam).

#### BED

BED file is located in `input/regions.bed.gz`.

### Output

Using [Nextflow](https://www.nextflow.io/), programming language and other tools of your choice implement the following:

1. Read counts for the regions specified in the provided BED file outputed as JSON.
2. Extract reads in the regions and convert it into a FASTA file where each entry consists of:
    ```
    >{READ_ID} 
    {READ_SEQUENCE}
    ```
3. You are free to use common bioinformatic tools but at least one step should be done via a bespoke script developed in a programming language of your choice. The bespoke script should have unit tests associated with it (it does not need to be extensive but just a functioning example of how you would test a function in your programming language of choice).

## Restrictions

- oneliner bash  script solutions involving a series of pipes will not be considered e.g. `program1 <INPUT_BAM> | program2 ...`

## Requirements

The following needs to be clearly specified:

1. Dependencies
2. Installation Instructions
3. Usage Instructions
4. How to run tests
5. Outputs

## Scoring

Things that will be considered:

1. `Workflow Design`
2. `Accuracy of Results`
3. `Ease of installation (dependency resolution)`
4. `Ease of running the workflow`

## Extra Considerations

In addition to the generation of correct outputs, the following is worth taking into consideration when designing or discussing the workflow:

1. `Design` 
2. `Test Implementation`
3. `CI`
4. `Reusability`
5. `Portability`
6. `Github History Management`

Following submission, the code and future development plan taking the above into consideration will be discussed.

## Submission

Share the repository with the code, documentation and commit history.

### Note
- if you would like to keep the repository private, please add `nm-johnny` or `nm-dcs` as a collaborator when ready to submit.
- if you prefer to use GitLab/Bitbucket please inform us and we will provide you the users to share the repository with.

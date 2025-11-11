# strut-issue-draft-5
struct Issue {
        EnumerableSet.AddressSet voters;
        string issueDesc;
        uint256 votesFor;
        uint256 votesAgainst;
            bool passed;
        bool closed;
    }

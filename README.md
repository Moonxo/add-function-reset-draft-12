# add-function-reset-draft-12
function resetMyGarage() external override {
        delete garages[msg.sender];
    }

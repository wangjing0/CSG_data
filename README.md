## Behavioral

### Behavior.mat

      CSG.MonkeyA :Main task in Monkey A
      CSG.MonkeyD :Main task in Monkey D
      CSG.Human   :Main task in Humans
      CSGrandom.Subject** : control task with probabilistic reward
      
### Format:
      Time_sec: Go event time stamps, in second
      Tt_ms: target interval, in ms
      Tp_ms: production interval
      Hand: 1, Hand; 0, Eye trial type
      Long: 1, Long interval; 0, Short interval trial type
      Left: 1, Saccadic target at left visual field; 0, right
      Reward: [0, 1] amount of reward normalized to the maximium value.
## Neural

### unzip this file: SpikingData.zip
 Two monkeys and three brain areas:  
     { 'Acortex';
      'Dcortex';
      'Acaudate';
      'Dcaudate';
      'Athalamus';
      'Dthalamus'}
  ### Format:    
      Tp_sec: production interval in second
      Rew: reward or miss
      TrialCondition: e.g. 'ELr' means Eye, Long, saccade target on the right
      EventTime_sec : time stamps of the four events(Cue, Tar, Set, Go) in each trial
      neuron_spktime: spike time for individual neuron 

## Behavioral data in 

Behavior.mat

      CSG.MonkeyA :Main task in Monkey A
      CSG.MonkeyD :Main task in Monkey D
      CSG.Human   :Main task in Humans
      CSGrandom.Subject** : control task with probabilistic reward
      
 format:
      Time_sec: Go event time stemps in second
      Tt_ms: target interval
      Tp_ms: production interval
      Hand: 1, Hand; 0, Eye trial type
      Long: 1, Long interval; 0, Short interval trial type
      Left: 1, Saccadic target at left visual field; 0, right
      Reward: amount of reward normalized to the maximium value.
## Neural data

unzip this file: SpikingData.zip

Two monkeys and three brain areas:  
     { 'Acortex';
      'Dcortex';
      'Acaudate';
      'Dcaudate';
      'Athalamus';
      'Dthalamus'}
  format:    
      Tp_sec: production interval in second
      Rew: 1 and 0's indicating reward or miss
      TrialCondition: e.g. 'ELr' means Eye, Long, saccade target on the right
      EventTime_sec : timestemps of four events(Cue, Tar, Set, Go) in each trial
      neuron_spktime: spiking timestep for neurons recorded simultaneously

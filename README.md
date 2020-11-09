# Behavioral data

Behavior.mat

      CSG.MonkeyA :CSG main task in Monkey A
      CSG.MonkeyD :CSG main task in Monkey D
      CSG.Human   :CSG main task in Humans
      CSGrandom.Subject** : CSG with probabilistic random reward given
  
# Neural data

start from this file: SpikingData.zip

  Two monkeys and three brain areas: 
     { 'Acortex';
      'Dcortex';
      'Acaudate';
      'Dcaudate';
      'Athalamus';
      'Dthalamus'}
      
      Tp_sec: production interval in second
      Rew: 1 and 0's indicating reward or miss
      TrialCondition: e.g. 'ELr' means Eye, Long, saccade target on the right
      EventTime_sec : timestemps of four events(Cue, Tar, Set, Go) in each trial
      neuron_spktime: spiking timestep for neurons recorded simultaneously
